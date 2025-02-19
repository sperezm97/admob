---
id: RequestOptions
title: RequestOptions
sidebar_label: RequestOptions
---

Request Options used to load the ad.

## Properties

### `requestNonPersonalizedAdsOnly`

Whether to load non-personalized ads only.

| Type    |
| :------ |
| boolean |

### `networkExtras`

Additional properties attatched to an ad request.

| Type                      |
| :------------------------ |
| { [key: string]: string } |

### `keywords`

An array of keywords to be sent when loading the ad.

| Type     |
| :------- |
| string[] |

### `contentUrl`

Content URL for targeting purposes. Max length of 512.

| Type   |
| :----- |
| string |

### `location`

The latitude and longitude location of the user.

| Type             |
| :--------------- |
| [number, number] |

### `requestAgent`

Content URL for targeting purposes. Max length of 512.

| Type   |
| :----- |
| string |