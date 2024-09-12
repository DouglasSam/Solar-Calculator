# Solar Calculator

This is a solar calculator part of the web app that was created for GovHack 2024.

It is in the React app using a iframe, and is written in PHP to handle the logic.

## GovHack

As mentioned this was created for GovHack 2024.

I was in the New Zealand team ATeamName with the project [GenEn](https://hackerspace.govhack.org/projects/genen).

The challenges that we had was 

- [Planning NZ’s electrical energy needs versus our generation capacity](https://hackerspace.govhack.org/challenges/planning_nz_s_electrical_energy_needs_versus_our_generation_capacity)
- [SolarZero Challenge: Driving Climate Action Through Self-Service Solar Discovery](https://hackerspace.govhack.org/challenges/solarzero_challenge_driving_climate_action_through_self_service_solar_discovery)

This part of the project handles the SolarZero challenge by giving users the ability to enter their address and some details about their power usage, and a potential solar array and will give details on how much switching to solar can save them.

## Project 

The final project covers a lot more and it a React Web App hosted [here](https://genen.andrewdevelops.com/). The calculator is in that web app through an [iFrame](https://genen.andrewdevelops.com/solar-calculator) and can be found on its own [here](https://bcis303.gladiatorsas.me/gh).

## The Technology

The logic is written in PHP and uses APIs from Google and when I get a valid key NIWA

### Google

I am using the Google Geolocator to get co-ordinated from an address, google embedded maps so users can confirm that it is the right address and to see the roof, and if applicable the Google Solar API which gives data on the buildings roof and how many solar panels can fit there.

### NIWA

I'm using NIWA solar view API to get information about solar in an area, however I do not have access to the required API yet because access requires approval so I have some hardcoded responses from their developer site and the method for the actual request still to go. 
