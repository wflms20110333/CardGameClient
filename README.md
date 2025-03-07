# Card Game Client

Presenting the Card Game Client, designed and developed at PennApps XX!

The Card Game Client is a way to play any card game with a standard 54 Card deck remotely by transmitting interactions between all participating players. Players can create a room or join an existing room with a central card deck. Interactions with the central deck (such as a user playing a card) are sent to all other users and displayed for them in real time.

The Card Game Client has a deal function, reset game function, and built-in chat to facilitate easy interaction between users, which allows the client to be flexible and play a wide variety of different games.

Created and demoed at PennApps XX (https://devpost.com/software/card-game-client).

[Presentation](https://docs.google.com/presentation/d/14l1-jkMfDBeRZ8H-gHlRFV8CMa_ai1_ZZat5Ec86Iic/edit?usp=sharing)

# Development/Setup Instructions

`pip install -r requirements.txt`

`python main.py`

Travel to http://localhost:5000 to see the initial landing game if deployed in this way.

The web app is located [here](https://amazing-ripple-252305.appspot.com). Users will need to sign in to their Google accounts, then either create a new game or join an existing game with a game code. Note: project not completely finished yet.

## Built With

- [Firebase Cloud Messaging](https://firebase.google.com/docs/cloud-messaging) - Cross-platform messaging solution
- [Flask](https://palletsprojects.com/p/flask/) - Web framework
- [SocketIO](https://socket.io/) - JavaScript library that enables realtime, bi-directional communication between web clients and servers
- [Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API) - Graphics API
- [CreateJS](https://createjs.com/) - Suite of modular libraries and tools

## Authors

- [Aditya Arjun](https://github.com/aditya-arjun)
- [Richard Guo](https://github.com/richardg999)
- [An Nguyen](https://github.com/aqn180001)
- [Elizabeth Zou](https://github.com/wflms20110333)
