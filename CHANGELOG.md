# Changelog

## [0.9.0](https://github.com/christianrowlands/network-survey-messaging/releases/tag/v0.9.0) - 2023-01-10
* Added a message schema for holding a Wi-Fi Probe Request record.
* Added a message schema for holding a Wi-Fi Deauthentication record.
* Added a various sensor metadata fields to the records.
* Added the mdmOverride field to the Device Status record.

## [0.8.0](https://github.com/christianrowlands/network-survey-messaging/releases/tag/v0.8.0) - 2021-10-26
* Added the `ecno` field to the UMTS Record.

## [0.7.0](https://github.com/christianrowlands/network-survey-messaging/releases/tag/v0.7.0) - 2021-09-09
* BREAKING CHANGE: Swapped the rawMessage for pcapRecord in the Cellular OTA messages.
* BREAKING CHANGE: Renamed the `lte_ota_message` topic to `cellular_ota_message` to allow it to be more generic.
* Added message schemas for GSM, UTMS NAS, and WCDMA RRC OTA messages (coming from Network Survey+).
* Added the accuracy field to all the messages which can be used to describe the accuracy of the provided location.

## [0.6.1](https://github.com/christianrowlands/network-survey-messaging/releases/tag/v0.6.1) - 2021-07-06
* Added the missionID and recordNumber fields to the Phone State message schema.

## [0.6.0](https://github.com/christianrowlands/network-survey-messaging/releases/tag/v0.6.0) - 2021-06-10
* Added a deviceModel field to the message schemas.
* Added a PhoneState message that is sent over the device_status_message topic that reports changes to the serving cell.

## [0.5.0](https://github.com/christianrowlands/network-survey-messaging/releases/tag/v0.5.0) - 2021-01-22
* Added a message schema for holding cellular LTE Over The Air (OTA) NAS messages.

## [0.4.0](https://github.com/christianrowlands/network-survey-messaging/releases/tag/v0.4.0) - 2021-01-19
* Added a message schema for 5G New Radio (NR) cellular survey records.
* Added a message schema for Bluetooth survey records.

## [0.3.0](https://github.com/christianrowlands/network-survey-messaging/releases/tag/v0.3.0) - 2020-12-18
* Added a message schema for holding cellular LTE Over The Air (OTA) RRC messages.

## [0.2.2](https://github.com/christianrowlands/network-survey-messaging/releases/tag/v0.2.2) - 2020-09-23
* Added a GNSS Survey message to the API.

## [0.2.1](https://github.com/christianrowlands/network-survey-messaging/releases/tag/v0.2.1) - 2020-08-19
* BREAKING CHANGES were made to the JSON output of the protobuf messages.
* Modified timestamps to use (RFC3339)[https://tools.ietf.org/html/rfc3339#page-6] date-time format.

## [0.2.0](https://github.com/christianrowlands/network-survey-messaging/releases/tag/v0.2.0) - 2020-08-11
* BREAKING CHANGES were made to the JSON output of the protobuf messages.
* Redesigned this messaging API to define the messages in JSON using AsyncAPI.
* Redefined the proto files to following the new JSON message schema.
* Deprecated the original proto definitions.
* Added a Signal Detection and an Energy Detection message to this API.

## [0.1.3](https://github.com/christianrowlands/network-survey-messaging/releases/tag/v0.1.3) - 2020-06-26
* Added the device_name field to all the wireless proto messages.

## [0.1.2](https://github.com/christianrowlands/network-survey-messaging/releases/tag/v0.1.2) - 2020-05-29
* Swapped out the 802.11 service set type from a String to an enum.

## [0.1.1](https://github.com/christianrowlands/network-survey-messaging/releases/tag/v0.1.1) - 2020-05-23
* Added a protobuf message for 802.11 beacon frames.

## [0.1.0](https://github.com/christianrowlands/network-survey-messaging/releases/tag/v0.1.0) - 2020-04-23
* Switched to the full java version instead of the java lite protobuf implementation.

## [0.0.2](https://github.com/christianrowlands/network-survey-messaging/releases/tag/release-0.0.2) - 2020-01-06
* Added support for streaming GSM, CDMA, and UMTS cellular survey records.

## [0.0.1](https://github.com/christianrowlands/network-survey-messaging/releases/tag/release-0.0.1) - 2019-09-27
* Initial release of message definitions.
