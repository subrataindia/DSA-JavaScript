# What is Async Storage ?

Async Storage is a community-maintained module for React Native that provides an asynchronous, unencrypted, key-value store. Async Storage is not shared between apps: every app has its own sandbox environment and has no access to data from other apps.

Don't use Async storage to store tokens or secrets.

It can be used for persisting non-sensitive data across app runs, redux state, graphql state etc.

React Native does not come bundled with any way of storing sensitive data. However, there are pre-existing solutions for Android and iOS platforms.

Android - Secure Shared Preferences

IOS - Keychain Services

