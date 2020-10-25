# WiCS Event Check-Ins

## Inspiration
The struggle of creating Google sign in form for every event, and manually having to track attendance. We also wanted to tackle the low attendance issue that we've been having with virtual events. One of the issues was a lack of reliable communication with WiCS members, that we aren't able to solve with just a messaging app or social media. The goal is to bridge the communication gap that we're currently experiencing. 

## What it does
As officers of the Women in Computer Science organization, we want to streamline sign ins for events and communication between the officers and members. This app is a central location to sign in to WiCS events. Members can submit feedback about an event as well, and are notified about upcoming events. Though this app isn't fully functioning as of yet, we hope to get it working to use in the future. 

## How we built it
We used Firebase for the backend work. Specifically, we use the Authentication feature provided by GCP and a basic Firestore database. 

## Challenges we ran into
Since both of us are beginners to GCP and Firebase (and Hackathons!), we had some issues with deployment and initializing a project from the ground up. After many failed attempts to deploy our web app that we wrote from scratch, we ended up turning to a template we forked from GitHub to give ourselves a better starting place. You can find the GitHub we forked from [here](https://github.com/chinchang/vuejsfire-hackathon-starter).

## Accomplishments that we're proud of
One thing that we're proud of, is that we were able to identify a problem and come up with a practical and effective solution to solve it. Although we didn't have the chance to completely flesh out and implement all of the features and aspects we had originally thought of, we're happy to have made the progress that we did. 

## What we learned
We learned a lot from the intro workshops! We attended the GCP + Firebase workshop as well as some of the beginner workshops and learned a lot about how to use Firebase, create a web app, and how to generally approach a hackathon project. 

## What's next for wics-events
One of the original ideas we had was to create a checkin app that relied on Geolocation. The initial plan was to create an app that took a user's Geolocation into account, and during the event time, would send a push notification to the user with the option to sign in, once they were in the event radius. We hope to implement this initial idea in the future!