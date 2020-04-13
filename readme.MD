[![Build Status](https://cloud.drone.io/api/badges/rpiambulance/at-channel/status.svg)](https://cloud.drone.io/rpiambulance/at-channel)

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://forthebadge.com)

# Campus OWL

**Campus Owl** is a MEAN stack application that allows users to create and update social media accounts that allow them to interact with other members of their campus community in safe, meaningful ways.


### Moderation

Moderation of this app will fall upon campus community members. In some cases it may make sense to allow campus administrators to moderate. In other cases, moderation may be left up to alumni or current students.

**Campus OWL** was designed for transparency, and as such, we have kept this project open source.

## Configuration

Setting up **at-channel** is pretty easy, requiring a few things configured on Slack, and a few environment variables set on your server's side.

### Environment variables

Using what you just set up on Slack, you now need to set up the server's environment variables. At this point, you should've cloned this repo to your server and run `npm i` to get all the packages squared away. Next, copy or rename the `.env.example` file to `.env`, and open it up. Fill out the fields accordingly (you will need a bunch of the information from Slack's app portal). When that's done, running `nodemon server.js` or running the server in whatever other way you choose should work!

## Credits

### Developers

- [Yaseen Mahmoud](https://github.com/ymmahmoud)
- [Daniel Schnoll](https://github.com/danielschnoll)
- [Austin Borina](https://github.com/austinborina)
- [Peter Gramenides](https://github.com/austinborina)

### License

**at-channel** is provided under the [MIT License](https://opensource.org/licenses/MIT).

### Contact

For any question, comments, or concerns, [create an issue](https://github.com/danielschnoll/ITWS-4500-WebSci-Project/issues/new), or open up a pull request.