# Secure IT
In this tutorial i will explain how to push the security of your IT hardware/software to it's maximum.

Now il will start with requirement, if you have done them this explainaition is totally useless :
1. DO NOT JAILBREAK APPLE HARDWARE OR ROOT ANDROID IT DESTROY ALL THE SECURITY OF APPLE/ANDROID HARDWARE.
2. DO NOT HACK WINDOWS MACOS OR YOUR ANTIVIRUS IT DESTROY ALL THE SECURITY IT NORMALLY PROVIDE TO YOU.
3. DO NOT DISABLE SECUREBOOT OR TPM SHIP BECAUSE YOU HAVE READ IT ON A LINUX FORUM.
4. DO NOT BLINDLY INSTALL A SERVICE WHO MUST SECURE YOUR PC/ANDROID/IOS THE OS DEFEND ITSELF VERY WELL.

If you have done point 1 leave this tutorial your security is totally destroyed congratulation.\
If you have done point 2 or 4 reset your OS before proceding to the next point.\
If you have done point 3 go back enable them in your BIOS / UEFI settings.

I will not cover Android in this guide because it's not securable in long term, since none of the one i have tested push all the security update every month.\
If you search security i will tel you better use Apple profuct, because they push update on all their device at the same time (not like Android).

## IOS (iPhone)

- First point very important, switch from a sim to an esim and disable the pin of it.

> Explaination
> - With e-sim and no pin your iphone will connect itself directly on your isp network and cannot be removed (even with unauthorised force reset).
> - This can only be removed/modified with the code of the user.
> - If you have that and IOS 15 your IOS phone will continue to appear on Find My network even if reseted and connected on network with the e-sim.
> - Disable the pin it's for letting it auto connect (and it does not reduce security since esim is on the motherboard so not removable like normal sim.

- Second Go to your Settings -> Icloud (with your photo) and check apple (or non apple hardware linked to your account and go to them to disconnect them (if not used let all hardware you acutally use), if you haven't them remove them.

> Explaination
> - This will remove access of old or unused hardware on your account and if you simply remove them the third point will finsh this force deconnection.

- Third in these settings go to Password and security, change your password with another one generated with https://spectre.app or https://masterpassword.app, like that the password can be complex the you can find it again even if you forget it.

> Explaination
> - Now only your new apple hardware (or used one you will reconnect will have access to your information.

- Fourth Buy or use 2 usb key (even low storage) and generate an encrypted partition in it with a password generated with https://spectre.app or https://masterpassword.app too (if possible use a mac, bebause mac apfs encrypted isn't as used as windows so it will reduce the possibility of someone try to crack it.

> Explaination
> - Like that you can easily recover your account if you loose acces to it (because two step on apple is only possible on already accepted hardware, the two usb key is for have a backup if one of them is lost, have a failure or destroyed and the recovery key is NOT WRITTEN ANYWHERE NOT ENCRYPTED.

- Fifth in your iphone enable the two factor authentication on your account and copy the emergency key to these two usb key, guard one of the two always on you and hide the other one at a safe place).

> Explaination
> - With that your Icloud account is secure and your ISP connection cannot be disabled buy removing the sim card.

- Sixth Go to Icloud Sync and check if KeyChain (Password manager) and Save of iphone is enabled.

> Explaination
> - It will sync your password between Apple Hardware and save the data of your iphone to avoid to lose infromation if you lose the Iphone or destroy it.

- Seventh Go to localise and check if localise is enabled, and share your postition.

> Explaination
> - It will do 3 things
> - One it will lock the activation of your iPhone (if someone stole you), your icloud account is the only one who can activate it.
> - Two it will let your iphone have location information.
> - Tree sharing will let appear your iphone on find my (if lost or stolen).

- Now Enable Faceid / TouchID and remove all acces when locked and move all your password and OTP to Apple KeyChain (password manager) and one it's done change ALL password and OTP of all of your services with differents password for every services, and add password from your Apple Account and the encrypted UsbKey.

> Explaination
> - With that all your password are secured, the two factore are also on apple so it's the only one who have your access, and if a services you use have been hacked and you don't know it you have secured it you can also copy the emergency code of all other services with otp to your two encrypted usb key.

- Finally Remove all app you don't use and sitch all your services who support it to Login With Apple (and remove them from the KeyChain) and check every settings in settings to be sure all of them is alright for you.

> Explaination
> - This will reduce attack surfaces (for the app removed), and pass on passwordless login with apple will increase the security of your account.

- Bonus tips : Reduce the screen enabled (without touch) to one minutes.

> Explaination
> - If your forget or don't really lock your phone it will prevent ill intentioned user to access to your Datas.

- Bonus tips 2 : Take an icloud+ account 0,99/month ans generate one email by services (hide my email), link your external domain (if you own one).

> Explaination
> - If your forget or don't really lock your phone it will prevent ill intentioned user to access to your Datas. 

- Congratulation your have easily secured your iPhone now pass to another Hardware if you have them.

## Ipad Os (Ipad)

- For now work the same as IOS (Iphone), if this change open an issue (if i don't have updated it).

## Mac Os (Mac)
- NOTE : Working on it offline will upload it here when finished

## Watch OS (Apple Watch)
- NOTE : Working on it offline will upload it here when finished

## Tv Os (Apple TV)
- NOTE : Working on it offline will upload it here when finished

## Router (falcultative but better)
- NOTE : Working on it offline will upload it here when finished
