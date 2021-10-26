# Firebase authentication

> A simple firebase-login system.

This login system uses firebase authentication (email and password), firebase firestore and hosting. Each user generates a UID, allowing the application to hold up to billions of users.

## Use

```
$ git clone https://github.com/LCordial/firebase-login.git
```

**Follow these steps:**

Once the repository has been cloned onto your computer, you'll need to install the firebase tools globally:
```
npm install -g firebase-tools
```
Once the firebase tools have been installed onto your system, follow these steps:
1. Open firebase in your browser and login with your google account.
2. Click `Add Project` and follow the prompts. (Disabling google analytics is recommended)
3. Now you'll need to make your project web based. Go to settings and scroll down to `Your apps`, then press `Add app`. Select `</>`
4. Run the command `firebase login` and follow the prompts.
5. Run `firebase init` within your project tree and follow the prompts. It is crucial that you select `hosting` and `firestore`.
6. Now you'll need to get the firebase config, which is in the project settings under `Your apps`.
7. Now, in the `index.html` file, 
```html
<script>
 // Replace with your firebase config
</script>
```

## License

[MIT License](https://github.com/LCordial/javascript-firebase-login/blob/main/LICENSE)
