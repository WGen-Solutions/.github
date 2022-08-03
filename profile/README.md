# WisdomCircle

- [Environments](#environments)
- [Branches](#branches)
- [Workflow](#workflow)
- [Repositories](#repositories)


## Environments
- [`Dev`](http://dev.wisdomcircle.com): This is the environment to which developers push their changes to test it outside of their local setup.
- `UAT`: This is the environment to which changes are pushed for being tested by internal stakeholders and non-developers.
- `Production`: This is the environment to which changes are pushed when they are ready to be made live.

## Branches
- `dev`: This is the main working branch from which developers make new branches for adding a new change.
- `uat`: This is the branch to which the code is pushed when they are ready to be tested by non-developers and internal stakeholders.
- `master` (or `main`): This is the branch to which the code is pushed when they are ready to be made live.

## Workflow
1. The changes that developers make, show up on the `Dev` environment (connected to the `dev` branch)
2. When the changes are ready to be tested by non-developers, they should be up on the `UAT` environment (connected to the `uat` branch)
3. Finally, after being thoroughly tested, the changes would be deployed on the `Production` environment (connected to the `master` branch)

## Repositories

Here is the description for each of the repositories.

### `wg_web_app`
The main web app that the user and recruiter interacts with.


### `wg_ms_master`
Microservice that holds master lists like skills, domains, etc. that serve as inputs for dropdowns in the frontend (web app and mobile app).


### `wg_ms_user`
Microservice for user-related services.


### `wg_ms_recruiter`
Microservice for recruiter-related services.


### `wg_ms_api_gateway`
Microservice for the API Gateway.

### `wg_ms_auth`
Microservice for authentication services.


### `wg_ms_communication`
Microservice for communication (email + SMS) services.


### `wg_admin_app`
Web App for the admin of WisdomCircle.

### `wg_mobile_app`
Mobile app that the user interacts with.
