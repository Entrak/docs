---
title: "Get Chatters"
num: 
version: 202310
---

Gets a list of users that are connected to the broadcaster's chat session.

| Box Name | Type | Description | 
|-------|--------|--------
Channel|String|Channel name to get chatters of
Save Variable As|String|Variable to save the result
{:class='table table-primary'}

| Chat Message Example | Description |
|-------|--------|--------
data|Object array|Array of objects containing the following info
&nbsp;&nbsp;&nbsp;&nbsp;user_id|String|The user's ID
&nbsp;&nbsp;&nbsp;&nbsp;user_login|String|The user's login name
&nbsp;&nbsp;&nbsp;&nbsp;user_name|String|The user's display name
total|Integer|The total number of users
{:class='table table-secondary w-auto table-hover data-toggle='table' text-break }