# Planned coding challenge: Memory lane

### Problem definition

After a series of discovery calls we found out a problem that our users are facing. They are having a hard time sharing their memories with friends and family. They are using a combination of social media, messaging apps, and email to share their memories. They are also using a combination of cloud storage, social media, and messaging apps to store their memories. They are looking for a solution that allows them to store and share their memories in a single place.

As a first iteration for this solution, we want to build a web application that allows users to create a memory lane and share it with friends and family. A memory lane is a collection of events that happened in a chronological order. Each event consists of a title, a description, a timestamp, and at least one image.

## Deliverables

- Clone this repository and create a new branch with your name. Open a pull request on your own instance of the repository.
- An updated README providing a high level explanation of your implementation.
- Update the API to accommodate for your technical design. Run the API by using `npm run serve:api`.
- The provided mockup is only for reference and inspiration. Feel free to improve it!

### Inspiration mockup

![Memory lane mockup](./memory_lane.png)

## Posting Memories

Users can create and post memories, which typically consist of text and optionally, images or other multimedia content.
Memories are timestamped upon creation and added to the user's memory feed.

## Editing Memories

Users can edit the content of their posted memories to correct mistakes or update information by clicking the three dots in the bottom right of the text area.

## Deleting Memories

Users have the option to delete any memory they have posted.

## Chronological Display

Memories are displayed in the order they were posted, with the most recent memory appearing at the top.
This chronological order is maintained through the use of a chained column.

## Stretch goals:

Added verification in form inputs
Likes and Comments: Allowing users to like and comment on memories, enhancing user engagement.
Notifications: Sending notifications to users when their memories receive likes or comments.
User login: Users can create an account by providing their email address, username, and password.
Privacy Settings: Giving users control over the visibility of their memories (public, private, friends-only).
