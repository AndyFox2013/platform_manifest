Beer Gang Project
================

To start, make a lovely folder to sync into. We tend to use:

    mkdir BeerGanging && cd BeerGanging
    
Then you need to initialize your local repo. Use this command:
    
    repo init -u git://github.com/BeerGangProject/platform_manifest.git -b jellybean
    
Then sync up:

    repo sync
    
Once you have synced, try building a device we support, just for giggles.

    .build/envsetup.sh
    
Then, you want to lunch up:

    lunch

Now pick the menu number. Eg. for the Nexus 4 (mako) you will want 10, so type 10.

Then, sync up again just to make sure you pull the changes for your device specific stuff.

    repo sync

Then, you want to make some bacon. Type:

    make bacon
    
Wait until it finishes.


    
Don't worry more will come. How to add device support etc.     
