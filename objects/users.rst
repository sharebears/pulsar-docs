Users
-----

APIKey
^^^^^^

.. parsed-literal::
  {
    "revoked": false,
    "user_id": 1,
    "hash": "abcdefghij",
    "ip": "127.0.0.1",
    "last_used": "1970-01-01T00:00:00.000001+00:00",
    "user-agent": "curl/7.59.0",
    "permissions": [
      "api_keys_view",
      "invites_send"
    ]
  }

* **revoked** - Whether or not the API key is revoked
* **hash** - The identification id of the API key
* **ip** - The last IP to access the API key
* **user-agent** - The last User Agent to access the API key
* **permissions** - A list of permissions allowed to the API key, encoded as ``str``

Invite
^^^^^^

.. parsed-literal::
  {
    "expired": false,
    "code": "an-invite-code",
    "time-sent": "1970-01-01T00:00:00.000001+00:00",
    "email": "bright@pul.sar",
    "from_ip": "0.0.0.0",
    "invitee": "<User>",
    "inviter": "<User>"
  }

* **expired** - Whether or not the invite is expired
* **code** - The invite code
* **time-sent** - When the invite was sent
* **email** - The email that the invite was sent to
* **from_ip** - The IP the invite was sent from
* **invitee** - The invited user
* **inviter** - The user who sent the invite

User
^^^^

.. parsed-literal::
  {
    "id": 1,
    "username": "user_one",
    "enabled": true,
    "user_class": "User",
    "secondary_classes": [
      "FLS",
      "Loser"
    ],
    "uploaded": 5368709120,
    "downloaded": 0,
    "email": "user_one@puls.ar",
    "locked": false,
    "invites": 1,
    "inviter": "<User>",
    "forum_post_count": 6,
    "forum_thread_count": 2,
    "api_keys": [
      "<APIKey>",
      "<APIKey>"
    ],
    "basic_permissions": [
      "perm_1",
      "perm_2",
      "perm_3"
    ],
    "forum_permissions": [
      "thread_1",
      "forum_2"
    ],
    "permissions": [
      "esoteric_perm_314"
    ]
  }

* **id** - The user's ID
* **username** - The user's username
* **enabled** - Whether or not the user is enabled
* **user_class** - Name of the user's user class
* **secondary_classes** - A list of the names of the user's secondary classes
* **uploaded** - The user's uploaded bytes
* **downloaded** - The user's downloaded bytes
* **email** - The user's email
* **locked** - Whether or not the user is locked
* **invites** - The user's invite count
* **inviter** - The user's inviter
* **forum_post_count** - The number of forum posts the user has made
* **forum_thread_count** - The number of forum threads the user has started
* **api_keys** - A list of the user's active API keys
* **basic_permissions** - A list of the user's basic permissions
* **forum_permissions** - A list of the user's forum permissions
* **permissions** - A full list of the user's permissions
