# mygroups-manageusers

## Overview
**mygroups-manageusers** is a PowerApps solution designed to manage Microsoft 365 and security group memberships. With this app, users can add or remove members from groups, view all members of a group, and update the `Security Enabled` parameter for M365 groups, allowing them to be used, for instance, in sharing a PowerApp.

## Demo Video
For a quick overview, watch the demo video: [mygroups-manageusers Demo](https://youtu.be/yUEgqOWdurc)

## Features
- **Membership Management**: Add or remove members in M365 and security groups.
- **Group Display**: View all members of a selected group.
- **Group Configuration**: Update the `Security Enabled` parameter of an M365 group.

## Technologies
This app only uses standard connectors:
- **Office 365 Groups** (Office-365-Groups connector)
- **Office 365 Users** (Office-365-Users connector)

A small Cloud Flow supports the `Security Enabled` parameter update for an M365 group, utilizing the **Office-365-Groups connector with HTTP Request version 2**.

## Languages
The app is available in **English** and **German**. The language can be set using a small translation variable within the app.

## Usage and License
The **mygroups-manageusers** app is free to use and share. However, no support or maintenance is provided for this solution.
