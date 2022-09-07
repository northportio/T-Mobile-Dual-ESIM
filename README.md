# T-Mobile Dual eSIM
A small write-up/resource for getting eSIM on your iPhone with two T-Mobile accounts

With the new iPhone 14 coming out and not including a physical SIM card slot, eSIM is the only option. For those that rock dual sim with two 
T-Mobile accounts (1 physical sim, 1 eSIM), the switch to two eSIMs can be a bit chaotic. After dealing with a very knowledgeable representative
(Shout out to Evan in Tennessee! He was awesome), I decided to document the steps below.

1. Call T-Mobile from another phone as you will be shutting off your cell plans in iOS. They will have to use a special system to override 
having two plans on one `EID`.
2. Go to Settings > General > About and note which `IMEI` is used by the physical SIM or is not in use. The section will be labeled with the 
label you created for the physical SIM cell plan. Also note the `EID`.
3. Remove the physical SIM. Then go to Settings > Cellular and tap the line that says no SIM. You will be prompted to update contacts.
4. Turn off the other lines with the toggle next to the phone number
5. Give the T-Mobile Rep the `IMEI` and `EID`
6. After a couple minutes, you should see a pop up in settings to enable the cellular plan. If not, you may have to go to Settings > Cellular >
Add Cellular Plan and scan [this](./eSIM-QR.png) QR code or enter the SM-DP+ Address: `T-MOBILE.GDSB.NET` leaving the Activation code blank and the 
confirmation code blank.
7. After it's enabled, make sure the cellular plan settings are what you want them to be (Ex: Primary Phone Line, Preffered Cellular Data line, etc.)

That's it!

 
