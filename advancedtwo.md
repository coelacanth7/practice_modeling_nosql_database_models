## You're building an activity feed for a social media site. The feed must display a chronological list of activities for the current user's friends. These activities could potentially be any action performed on the site including uploading a photo, changing their profile, friending another user, commenting, liking etc... Further, you only want to display activities for users that the current user interacts with frequently.

## USER profile:

{
  * Type: userprofile
  * Username: string
  * friends: [array of usernames]
  * friends that interact with frequently: [ array of usernames ]

}

## activity feed

{
  * Type: activity feed
  * foruser: Username
  * activities: {
    * activity: {
      * action: string
        * could be changing profile pic, updating status
      * user that committed: Username
      * Time: dateTime
      
    }

  }

}
