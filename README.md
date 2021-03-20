# firebase-login

> A simple web firebase-login system.

## Use

```
$ git clone https://github.com/LCordial/firebase-login.git
```
**Follow these steps:**

Once the repository has been cloned onto your computer, you'll need to install the firebase tools globally using this command:
```
npm install -g firebase-tools
```
Once the firebase tools have been installed onto your system, follow these steps:
1. Open firebase in your browser and login with your google account.
2. Click `Add Project` and follow prompts. (Disabling google analytics is recommended)
3. Now you'll need to make your project web based. On the main page within your project, click the icon `</>` to enable web based applications.
4. In your chosen IDE and in your terminal run the command `firebase login` and follow the prompts.
5. After you have logged into your chosen google account run `firebase init` within your project tree and follow the prompts. It is crucial that you select `hosting` and `firestore`.
6. Once you are done, head back into the firebase project and grab your firebase config. Which is in the project settings and under `Your apps`.
7. Now, in the `index.html` file, add your firebase config that says `Replace with your firebase config`. DO NOT DELETE `firebase.initializeApp(firebaseConfig);`
8. And know you are all good to go! Have fun!

## Contributions
Help weed out bugs that may be in this project. Or ask for more features! To do this, use the amazing feature called `Issues`
