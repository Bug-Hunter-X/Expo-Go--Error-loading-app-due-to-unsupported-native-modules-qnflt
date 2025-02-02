# Expo Go Error: Unsupported Native Modules

This repository demonstrates a common issue encountered when developing React Native applications with Expo and attempting to run them within the Expo Go client.  The problem arises when your app utilizes a library that relies on native modules, which are not supported by Expo Go.

## Problem

When you try to run an app that depends on a native module library in Expo Go, you often encounter an obscure error. This is because Expo Go's primary purpose is to provide a quick and easy way to test apps, but it has limitations in its ability to support libraries requiring native platform code.

## Solution

The solution involves two main approaches:

1. **Find Alternatives:** The simplest and often best solution is to find alternative libraries that provide the same functionality but without needing native modules. Look for libraries that are Expo compatible.

2. **Eject from Expo:** If a suitable alternative doesn't exist, the only option is to eject your project from Expo and use a fully native approach.  This grants complete control and allows the inclusion of any necessary native modules, but increases the complexity of the project.

This example showcases the problem and provides guidance on how to fix it by replacing the problematic library.

## Setup

1. Clone this repository
2. Run `npm install` or `yarn install`
3. Observe the error in Expo Go
4. Try the solution (replace problematic library)