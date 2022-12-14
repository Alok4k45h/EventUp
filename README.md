# Eventup

Eventup is a website where we can choose to attend an event (either physically or virtually) based on our interest.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Your machine should have NPM(or yarn), NodeJS and MongoDB installed to use eventup locally.

## Setup and Installation

### Setting up the repository locally

1. First fork the repo to your account.  
   Go to the forked repo and clone it to your local machine:

```
git clone https://github.com/<your_username>/eventup.git
```

This will make a copy of the code to your local machine.

2. Now move to the `eventup` directory.

```
cd eventup
```

3. Now check the remote of your local code by:

```
git remote -v
```

The response should look like:

```
origin	https://github.com/<username>/eventup.git (fetch)
origin	https://github.com/<username>/eventup.git (push)
```

To add upstream to remote, run:

```
git remote add upstream https://github.com/Cyber-Labs/eventup.git
```

Again run `git remote -v`, the response should look like:

```
origin	https://github.com/<username>/eventup.git (fetch)
origin	https://github.com/<username>/eventup.git (push)
upstream	https://github.com/Cyber-Labs/eventup (fetch)
upstream	https://github.com/Cyber-Labs/eventup (push)
```

4. Once the remote is set, install all the necessary dependencies by the following command:

```
npm run install-all
```
### Run locally

Run the below command to start the backend and frontend server:

```
npm run dev
```
Go to: [http://localhost:3000](http://localhost:3000)