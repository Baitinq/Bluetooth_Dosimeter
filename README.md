
# Bluetooth Dosimeter

Hi! Bluetooth Dosimeter is a simple, modular and extensible Bluetooth contact tracker. 
  

## Rationale

There currently exists many apps and services which can help people trace, track and or compare physical contact data. These current mass-data gathering and centralised approaches carry many privacy and security risks, hence the niche of this service, which aims to provide a similar service without the centralisation and data storage.

This service attempts to deliver on these claims by providing a self-hosted, offline and no-data-storage service which focuses on totally on the user instead on a collection of users.

Although this limits the scope and functionality of the service, I believe the aforementioned privacy and security related advantages would offset the "decreased" functionality, while also having the major advantage of obtaining more trust from users which would more likely use the service.

## Building & Running

### Build

#### Fetch the git submodules

    git submodule update --init --recursive

    git submodule update --remote --merge

#### Build the docker image

    docker-compose build

### Run

    docker-compose up

  

## Usage

  
Press the start recording button in the homepage to start recording a new contacts session. Live analysis and comparisons will be generated in the analytics page. You can export and import the recorded data in the different analytics' tabs.

To change any kind of setting including the API's endpoint, head over to the settings page.
