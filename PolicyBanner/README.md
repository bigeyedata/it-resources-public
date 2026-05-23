# Policy Banner Directory

This directory contains the policy banner file that is displayed to users on all laptops before login.

## Overview

The policy banner file in this directory is synced automatically updated by an external script executed by our MDM solution. This ensures that all devices display the current policy acceptance notice at login time.

## Contents

- **PolicyBanner.rtf** - The policy acceptance banner displayed to users before login

## Update Process

The banner file is updated automatically through:

- MDM-triggered scripts that run on a scheduled basis

## Usage

The policy banner is displayed during the login process on all managed laptops. Users must acknowledge the policy before proceeding to log in.

## Notes

- Changes to the policy should be made directly to this file.
