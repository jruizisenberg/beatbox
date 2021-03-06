Beatbox
======
Beatbox is an iPad app for App.net. Much like the tortoise in the Aesop fable, I am slowly but steadily making it awesome.

##### Using the source ######
- Clone the source
- Run 'git submodule init', followed by 'git submodule update'
- Open ADNConfig.h, and input your own client_id, callback, and scopes needed

Voila! You should be good to go.

##### Using the app #####
When the app starts, you'll need to login. The app will redirect you to the App.net authentication page, where you'll need to input your credentials. Once you do that, you'll be redirected back to the app through the use of some registered URI scheme trickery. At this point, the app should have an access_token, which can be used to make API calls on behalf of the user.

##### How you can help #####

Interested in helping out? The area I'm most lacking is graphic/asset creation, so if someone wants to help with UI design, and create icons, buttons, textured backgrounds, etc, it would be greatly appreciated.

##### Contact #####

Ryan Gerard (@g on app.net, @dreadpirateryan on twitter, [email](mailto:ryan.gerard@gmail.com))
