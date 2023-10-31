# 🎬 The Ultimate Guide to Immutable Passport Integration: A Cinematic Journey 🚀

## Table of Contents

- [Introduction](#introduction)
  - [About Immutable Passport](#about-immutable-passport)
  - [Purpose of this Guide](#purpose-of-this-guide)
  - [Prerequisites](#prerequisites)
- [Chapter 1: Setting Up Your Application](#-chapter-1-setting-up-your-application)
- [Chapter 2: Registering Your Application](#-chapter-2-registering-your-application)
  - [Step 1: Signing in to Your Immutable Developer Hub Account](#-step-1-signing-in-to-your-immutable-developer-hub-account)
  - [Step 2: Registering Your Application](#-step-2-registering-your-application)
- [Chapter 3: Installing and Initializing the Passport Client](#-chapter-3-installing-and-initializing-the-passport-client)
- [Chapter 4: Logging in a User with Passport](#-chapter-4-logging-in-a-user-with-passport)
- [Chapter 5: Displaying User Information](#-chapter-5-displaying-user-information)
- [Chapter 6: Logging Out a User](#-chapter-6-logging-out-a-user)
- [Chapter 7: Initiating a Transaction from Passport](#-chapter-7-initiating-a-transaction-from-passport)
- [Epilogue: The Grand Finale](#-epilogue-the-grand-finale)
- [References and Further Reading](#-references-and-further-reading)

## Introduction

### About Immutable Passport

Immutable Passport is a revolutionary feature simplifying blockchain onboarding for the masses, driving mass adoption. It offers a user-friendly experience with features such as covering gas fees for first-time users, enabling funding with credit or debit cards, frictionless onboarding, and robust identity verification. Immutable Passport serves as a bridge between traditional and blockchain gaming, making blockchain technology accessible to a broader audience. To learn more, visit the [Immutable Passport product page](https://www.immutable.com/products/passport).

### Purpose of this Guide

The purpose of this guide is to provide comprehensive instructions and insights for integrating Immutable Passport into your application. By following this guide, developers and users will be able to harness the full potential of Immutable Passport's user-friendly features and its role in simplifying blockchain onboarding. Whether you're a seasoned developer or new to the world of blockchain technology, this guide aims to make the integration process straightforward and accessible. It serves as a valuable resource for driving mass adoption by breaking down entry barriers, including gas fees and the need for cryptocurrency, ultimately bridging the gap between traditional and blockchain gaming.

### Prerequisites

Before you start, ensure that you meet the following requirements:

- **Node.js and npm (Node Package Manager):** Make sure you have Node.js and npm installed on your system.

- **Code Editor:** You will need a code editor for working with the code. Popular options include Visual Studio Code, but you can choose any code editor of your preference.

- **Immutable Developer Hub Account:** You must have an account on the Immutable Developer Hub to access the necessary resources.

In addition, it's beneficial to have the following:

- **Basic Understanding of JavaScript and Node.js:** While this guide aims to be beginner-friendly, having a basic understanding of JavaScript and Node.js will be helpful.


Ah, welcome, my fellow developers, to the grand adventure of integrating Immutable Passport into your application! If you've ever dreamt of securing your application with blockchain magic and simplifying user onboarding, you're in for a treat. Imagine this guide as a thrilling movie, with you as the hero, and Immutable Passport as your trusty sidekick. 🎥

## 🚀 Chapter 1: Setting Up Your Application

![Movie Scene: The Setup](https://your-image-url-here)

In this opening scene, you have two choices, just like in the movies. You can either start from scratch, creating a custom Next.js application that's as unique as you are, or you can clone a pre-built repository for a quicker start. It's like choosing between crafting your own superhero costume or borrowing Iron Man's suit. Your call! 😉

- **Creating a Basic Application**: Craft your Next.js masterpiece with:
  ```
  mkdir my-immutable-app
  cd my-immutable-app
  npm init -y
  npm install @immutablex/passport
  ```
  
- **Cloning a Pre-built Application**: If time is of the essence, just clone the repository like a seasoned explorer.
  ```
  git clone <"url of the GitHub repo that you want to clone">
  cd <"name of the cloned repo">
  npm install  
  ```

## 📋 Chapter 2: Registering Your Application

![Movie Scene: The Registration](https://your-image-url-here)

### 🚀 Step 1: Signing in to Your Immutable Developer Hub Account

Your journey kicks off with the first crucial step – signing in to your Immutable Developer Hub account. If you haven't created an account yet, fret not! We'll guide you through the process.

- **Visit the Immutable Developer Hub website**: Your portal to the world of blockchain possibilities awaits. Head over to the [Immutable Developer Hub website](https://www.immutable.com/developer-hub) and prepare for an exciting voyage.

- **Choosing Your Entryway**: As you reach the homepage, your options emerge like the unfolding plot of a suspenseful movie. If you already possess an Immutable Developer Hub account, the "Sign In" option is your gateway to continue your adventure. However, if you're a newcomer to this captivating universe, you have two intriguing paths to choose from: "Create Account" or "Sign Up." Select your preferred entry point to create a new account.

- **Guided Registration**: The Immutable Developer Hub's intuitive registration process is akin to a seasoned script, guiding you step by step through the intricate storyline of account creation. Follow the on-screen instructions, and with each click, you are weaving a tale that will grant you access to the incredible world of Immutable.

### 🌟 Step 2: Registering Your Application

This is the defining moment, the climax of your registration adventure. Here, you'll acquire your "Client ID," a precious key that opens doors to the blockchain kingdom.

- **Selecting Your Application Type**: Within the Immutable Developer Hub, you'll find the crucial "My Applications" or "Create New Application" option. The choice between them may remind you of a plot twist in a suspense thriller. Depending on the interface, click on the one that aligns with your mission.

- **The Web Application Route**: As of the time of writing, "Web Application" is the shining star, the only available application type. This is your vehicle for integration, so select it with confidence.

- **Naming Your Application**: In the realm of blockchain, your application needs a distinctive identity. Your "Client Name" serves as the character name for your application in this digital saga. Make it memorable, make it unique.

- **Exit Strategies: Logging Out Securely**: In your application, the ability to log out securely is akin to the thrilling escape sequence in a suspenseful movie. The "Logout URLs" section is where you define the secure locations where users can safely conclude their digital journeys. These URLs should direct users to the logout functionality of your application.

- **Callback for Integration**: The integration plot thickens as you reach the "Callback URLs" section. Here, you ensure that your application's callback URL aligns perfectly with what you've provided during the Passport client's initialization. This is the key to seamless integration, where every detail matters.

- **Completing the Application Saga**: The climax is near as you follow the on-screen instructions to complete the registration process. This could include solemnly agreeing to the terms and conditions, or tailoring additional settings based on your application's unique requirements. The final scenes of this chapter bring a sense of fulfillment as you register your application successfully, opening doors to a world of blockchain possibilities.

### 🔑 Obtain Client Credentials

With the registration of your application comes the prized possession – your "Client ID." This unassuming but powerful code is essential for authentication and authorization, a master key to access the blockchain's hidden chambers.

With these steps, you will have successfully registered your application on the Immutable Developer Hub, obtained the crucial Client ID. Remember, in the world of blockchain, secrecy and best practices are your allies.

*The registration chapter concludes with a sense of achievement, as you equip your application for a journey into the heart of blockchain adventure. Keep your credentials close, and let the blockchain saga continue.* 🚀


## 🌐 Chapter 3: Installing and Initializing the Passport Client

![Movie Scene: The Tech Enigma](https://your-image-url-here)

As our hero, you'll need to understand the technical details of this adventure. Installing the Passport Client is like receiving your superhero suit's user manual. 🦸‍♂️

- **Installing Dependencies**: Grab the tools you'll need:
```bash
npm install express --save
npm install @imtbl/sdk --save
```
- **Initializing the Passport Client**: Our Passport client is your trusty sidekick for secure authentication and authorization. We set it up like a pro.
```
// Import the Passport class from the 'immutable-passport' library
const { Passport } = require('immutable-passport');

// Create a new Passport instance with the required configuration
const passport = new Passport({
// Replace 'YOUR_CLIENT_ID' with your actual Client ID obtained from the Immutable Developer Hub
clientId: 'YOUR_CLIENT_ID',

// You can add other configuration options here as needed
// Additional configuration options can be added based on your application's requirements.
// For instance, you might configure scopes, logging, or other settings.
});
```
The 'passport' instance is now prepared for seamless integration into your application, serving as the bridge for authentication and authorization.

## 🚪 Chapter 4: Logging in a User with Passport

![Movie Scene: The Hero's Welcome](https://your-image-url-here)
```
// Import the Passport provider from the 'immutable' library
import { passportProvider } from "@/lib/immutable";

// Define a function to initiate user authentication with Immutable Passport
const loginWithPassport = async () => {
  try {
    // Request user account access through the Passport provider
    const accounts = await passportProvider.request({
      method: "eth_requestAccounts",
    });

    // If the request is successful, the user is connected
    console.log("User Connected");
    console.log(accounts);
  } catch (error) {
    // Handle authentication errors
    errorHandling("Authentication error", error);
  }
};

// Call the loginWithPassport function when needed to trigger the authentication process
loginWithPassport();
```

It's time for action! We've got code snippets that'll show you how to securely log in a user using Immutable Passport. It's like a grand welcome to the superhero team. 🦸‍♀️

## 🎭 Chapter 5: Displaying User Information

![Movie Scene: The Big Reveal](https://your-image-url-here)

Let's reveal the user's vital information. Show the user's ID token and access token like revealing a superhero's true identity. 🕵️‍♀️

```
import { passportInstance } from "@/lib/immutable";

// Define a function to fetch user information from Immutable Passport
const fetchUserInfo = async () => {
  try {
    // Fetch the user's profile information
    const userProfile = await passportInstance.getUserInfo();

    // Fetch the access token and ID token
    const accessToken = await passportInstance.getAccessToken();
    const idToken = await passportInstance.getIdToken();

    // Display user information in your application
    console.log("User Profile:", userProfile);
    console.log("Access Token:", accessToken);
    console.log("ID Token:", idToken);
  } catch (error) {
    // Handle errors when fetching user information
    console.error("Error fetching user information:", error);
  }
};

// Call the function when needed to display user information
fetchUserInfo();

```

## 🚪 Chapter 6: Logging Out a User

![Movie Scene: The Bittersweet Farewell](https://your-image-url-here)

A hero always knows when to exit gracefully. Logging out is like waving goodbye to a trusted friend. 😢

```
// Import the required libraries or instances
import { passportInstance } from "@/lib/immutable";
const passport = require('./index');

// Define a function to log out a user
const logoutUser = async () => {
  try {
    // Trigger the Passport logout process through the Passport instance
    await passportInstance.logout();
    
    // Redirect the user to the login page after successful logout
    window.location.href = '/login';
  } catch (error) {
    // Handle any potential errors during the logout process
    errorHandling("Logout error", error);
  }
};

// Call the function when the user initiates the logout process
logoutUser();
```

## 💰 Chapter 7: Initiating a Transaction from Passport

![Movie Scene: The Epic Battle](https://your-image-url-here)

```
// Import the necessary modules from the 'immutable' library
import express from 'express';
import { initiateTransaction } from '@/lib/immutable';

// Create an Express application
const app = express();

// Define a route for initiating a transaction
app.get('/transaction', async (req, res) => {
  try {
    // Define the transaction data and parameters here
    const transactionData = {
      to: 'YOUR_RECIPIENT_ADDRESS', // Replace with the recipient's address
      value: '1000000000000000000', // Specify the value in Wei
      data: 'Hello There !!!', // Add any necessary transaction data
      // Additional parameters can be included here as needed
    };

    // Use the 'initiateTransaction' function to send the transaction data
    const transactionHash = await initiateTransaction(transactionData);

    // Log the transaction initiation success and send a response to the client
    console.log(`Transaction initiated with hash: ${transactionHash}`);
    res.send(`Transaction initiated with hash: ${transactionHash}`);
  } catch (error) {
    // Handle errors during transaction initiation
    console.error(error);
    res.status(500).send('Error initiating transaction');
  }
});

// Start the Express server on port 3000
app.listen(3000, () => {
  console.log('Server started on port 3000');
});

```

Every great adventure deserves an epic climax. In this chapter, you'll learn how to initiate transactions with Immutable Passport. It's like the final showdown in a blockbuster movie! 💥


## 🎬 Epilogue: The Grand Finale

![Movie Scene: The Triumph](https://your-image-url-here)

In this cinematic journey of Immutable Passport integration, we aim to simplify blockchain onboarding and promote mass adoption. Immutable Passport offers a user-friendly experience, covering gas fees, credit/debit card funding, and robust identity verification. Whether you're a seasoned developer or new to blockchain, this guide equips you to harness its features, bridging traditional and blockchain gaming. From registration to initiating transactions, this adventure makes blockchain accessible and exciting. So, get ready to embark on this thrilling journey and let the blockchain saga continue! 🚀🎬

## 📜 References and Further Reading

To explore more about Immutable Passport and the options it offers, you can refer to this links:
- [Immutable Passport documentation](https://www.immutable.com/products/passport).
- [Immutable Developers](https://www.immutable.com/developers)
- [Immutable Community Connect](https://www.immutable.com/community/connect)
- [Immutable Company](https://www.immutable.com/company)


With that, you've reached the end of this thrilling movie-like guide to integrating Immutable Passport into your application. 🍾 Lights, camera, action! Go forth and build incredible, secure applications with Immutable Passport by your side. Cheers to your blockbuster success! 🥂🎉
