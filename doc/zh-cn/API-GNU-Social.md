# GNU Social API

* [首页](help)
  * [使用API](help/api)

## 概述

Friendica在[官方GNU Social类Twitter API参考文献](https://gnusocial.net/doc/twitterapi)中定义了以下终端节点。

认证方式与[使用API](help/api#Authentication)中描述的相同。

## 实体

这些终端节点使用[Friendica API实体](help/API-Entities)。

## 已实现的终端节点

- GET api/account/rate_limit_status
- POST api/account/update_profile_image
- GET api/account/verify_credentials

- GET api/direct_messages
- POST/DELETE api/direct_messages/destroy
- POST api/direct_messages/new
- GET api/direct_messages/sent
- GET api/favorites
- POST api/favorites/create/:id
- POST api/favorites/destroy/:id
- GET api/followers/ids
- POST api/friendships/destroy
- GET api/friends/ids
- GET/POST api/help/test
- GET api/search
- GET api/statuses/show/:id
- POST api/statuses/destroy/:id
- GET api/statuses/followers
- GET api/statuses/friends
- GET api/statuses/friends_timeline
- GET api/statuses/friends_timeline/:username
- GET api/statuses/home_timeline
- GET api/statuses/mentions
- GET api/statuses/replies
- GET api/statuses/replies/:username
- POST api/statuses/retweet/:id
- GET api/statuses/public_timeline
- POST api/statuses/update
- GET api/statuses/user_timeline
- GET api/users/show

## Non-implemented endpoints

- statuses/retweeted_to_me
- statuses/retweeted_by_me
- statuses/retweets_of_me
- friendships/create
- friendships/exists
- friendships/show
- account/end_session
- account/update_delivery_device
- account/update_profile_background_image
- notifications/follow
- notifications/leave
- blocks/create
- blocks/destroy
- blocks/exists
- blocks/blocking
- oauth/authorize
- oauth/access_token
- oauth/request_token
- statusnet/groups/timeline
- statusnet/groups/show
- statusnet/groups/create
- statusnet/groups/join
- statusnet/groups/leave
- statusnet/groups/list
- statusnet/groups/list_all
- statusnet/groups/membership
- statusnet/groups/is_member
- statusnet/tags/timeline
- statusnet/media/upload
- statusnet/config
