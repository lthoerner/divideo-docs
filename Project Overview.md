This section provides a general look at the project and its proposed features. If you want information on how it will actually be implemented, visit the [[Implementation Details]] page.

## Introduction
Divideo is a federated video sharing platform. It aims to be an alternative to major platforms, such as YouTube, whilst providing much more robust monetization options than existing alternatives like PeerTube. Content creators on the Divideo network have complete control over their own content and freedom to choose how they monetize it.

## Software Components
There are four major components that compose the Divideo network.
### 1. Streaming Client
- Available as a web app and a mobile app
- Browse videos by connecting either to an indexing server, or directly to a content server
- Stream videos served by content servers
- Interface similar to YouTube
	- Video player
	- Search functionality
	- Recommendation feed
### 2. Content Servers
- Creators can upload and manage their content
- Analytics for hosts/creators
	- Server hosting analytics (bandwidth/hardware utilization etc.)
	- Content analytics (viewership, ratings, etc.)
- Multi-channel access system to support content aggregation platforms
- Integration with cloud platforms such as AWS
- Horizontal and vertical scalability
### 3. Indexing Servers
- Allow users a convenient way to browse multiple content servers simultaneously
- Provide much better discoverability to content servers
- Curation and moderation force to make the platform friendlier to prospective users
- Hierarchical system for indexing both content servers and other index servers
### 4. Authentication Servers
- Provide user verification to content servers
- Greatly reduce the administrative overhead caused by needing to moderate comments, ratings and other user interactions

## First-Party Platform
In addition to the software that we are developing, the team at Divideo has plans to host a "default" indexing server and authentication server. In conjunction with the first-party user client, we feel that this is the best way to make the platform extremely approachable to new users, without sacrificing the core tenets of a federated network.
To expound on this concept a bit, the goal is to provide all the necessary tools for both creators and viewers to use the network however they see fit. We welcome tinkerers and power users with open arms; we also feel strongly that the average user must have the most seamless experience possible in order to compel them to use the platform regularly. The way we are constructing the Divideo system should fit the needs of the entire spectrum of its users, from the avid Gentoo enthusiast to the tech-illiterate father-in-law.