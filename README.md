# Silversky_Classifier

*Is the John Mayer signiture PRS Silversky a stratocaster clone?*

This is the question I set out to answer - by retraining a tensorflow neural network (using transfer learning) and feeding it pictures of PRS guitars and Stratocasters. 
After this I asked it to classify a few pictures of the SilverSky - results below!

# Control Photos
**Testing to see the trained models accuracy on a PRS and Strat**

*PRS*

![prscontrol](https://user-images.githubusercontent.com/35103224/39095834-e4e25268-463e-11e8-8388-be4cf541e315.jpg)

![image](https://user-images.githubusercontent.com/35103224/39095855-2e6fec60-463f-11e8-8ee2-4d92472c8d69.png)
**97% PRS**
**3% Strat**

*Stratocaster*

![image](https://user-images.githubusercontent.com/35103224/39097746-736abd36-4658-11e8-92f1-3dc01d0789c9.png)

![image](https://user-images.githubusercontent.com/35103224/39095876-9968f318-463f-11e8-9ef0-601cf09dc59e.png)
**99% Strat**
**1% PRS**

Looks like our model is working quite well

# Silversky results

I tested 4 Silversky pictures;

1) Headstock (Expecting: High PRS %)
![ss1](https://user-images.githubusercontent.com/35103224/39095886-cac1aed2-463f-11e8-900c-461d77eb814c.jpg)

![image](https://user-images.githubusercontent.com/35103224/39095892-ee379570-463f-11e8-85b3-3f4be7905f9e.png)

**Result: High PRS %**

2) Angled Body shot (Expecting: Medium PRS %)
![ss2](https://user-images.githubusercontent.com/35103224/39095909-1b0e25aa-4640-11e8-9050-63c243d4f7f7.jpg)

![image](https://user-images.githubusercontent.com/35103224/39095919-35ab5112-4640-11e8-9ad6-b41cad72540e.png)

**Result: High PRS % - Probably due to fretboard inlays**

3) Silversky banner pic (Expecting: Med-High strat %)
![ss3](https://user-images.githubusercontent.com/35103224/39095940-7a3e360a-4640-11e8-95c0-b278cfdb75c2.jpg)

![image](https://user-images.githubusercontent.com/35103224/39095944-8f1d2946-4640-11e8-9a68-1d1f0e75ba70.png)

**Result: High Strat % - Headstock is missing so probably drives Strat % up**

4) Full body shot (Expecting: High Strat % but less than pic 3)
![ss4](https://user-images.githubusercontent.com/35103224/39095952-bad9a244-4640-11e8-9f1d-77fceafb20f2.jpg)

![image](https://user-images.githubusercontent.com/35103224/39095962-de0a8076-4640-11e8-8564-26cef4b6aee8.png)

**Result: High strat % (shocker)**

# Conclusion
This was probably a useless test - everyone knows Telecasters are the best guitars anyway, ok. 


