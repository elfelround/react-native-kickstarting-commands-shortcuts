

********************START EMULATOR************************


cd ~/Android/Sdk/tools && ./emulator -avd Nexus_6_API_22


*********************************************

remember to run ifconfig and change the ip on the code with your new ip


//open studio code
//ctrl+` for terminal

mkdir LGBTQ
cd LGBTQ
react-native init mobile
mkidr backend
cd backend
npm init --yes // yes for defaults and not prompting options
yarn add express socket.io

cd ..
code .
crt+`

create index.js in backend, fill with socket.io .on and .listen logging

cd backend
npm i -g nodemon //-g global, can enter nodemon anytime in console
***********RUN BACK SERVER
nodemon index.js //realtime updates from code to dev

new terminal button (+)

************emu without A studio**************

cd ~/Android/Sdk/tools/bin && ./avdmanager list avd
//outputs list of emulators installed

##Copy name of device you want to run and then

cd ~/Android/Sdk/tools && ./emulator -avd NAME_OF_YOUR_DEVICE

##in my case:
##******************************************
********************************************
cd ~/Android/Sdk/tools && ./emulator -avd Nexus_6_API_22
*********************************************


//have the android emulator open

anothers console
cd mobile
react-native run-android

clean the app.js, ill make sure to initiate git and commit before this so cleaning is in another commit

cd LGBTQ
git init
git config user.name "mr-programs"
git config user.email "livingandwasting@hotmail.com"
// might wanna add node-modules to .gitignore in this step
git commit -m "base code, server runs and logs, app doesnt query yet"
// might wanna make a gitlab private repo
//case repo
//git remote add origin https....git
//git push -U origin master (no longer needed after)

//mobile console
yarn add socket.io-client  (because we only need the client

committed before adding stuff

ifconfig (requires net-tools installed, similar to ipconfig to check our local address)
