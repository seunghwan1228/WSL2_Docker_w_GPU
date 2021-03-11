<br/><br/>
# Install WSL2 and Docker with GPU availiable

 - [Han](https://github.com/seunghwan1228) 
---

# Workstation Setting with Windows preview build and docker with gpu support

---

---
# 1) Windows Build > 20145 or higher
   - !! CAUTION: WINDOW VERSION 21327 Does not Work CUDA, so DO NOT USE THIS BUILD
<br/><br/><br/><br/>

## How to get Window Preview Build?
<br/><br/>
### 1. Log-in your window OS as Administrator

![Log-in-Account](assets/window_login.png)

<br/><br/>

### 2. Join Window Insider Program

- Register as the same account with your OS logged-In

[https://insider.windows.com/en-us/register](https://insider.windows.com/en-us/register)

You will see this after register

Click 
```
Get started
```

![after register](assets/after_register.png)



- Follow the Guid

![flight](assets/update_flight.png)
<br/><br/>
## Need to change your update setting

![setting_1](assets/insider_setting_1.png)
```
click 

Go to Diagnostics & Feedback settings to turn on optinal diagnostic data.
```
![setting_2](assets/insider_setting_2.png)
![setting_3](assets/insider_setting_3.png)

<br/><br/>
## Set a Channel  - (I choosed Dev-Channel)

![select_channel](assets/insider_setting_channel.png)
<br/><br/>

## Finally Ready to get Preview Build
![after login](assets/how_should_look.png)
<br/><br/>
##  Start Update :smile:

Click
```
Check Update
```
there will the latest window build start with 21xxx (Mar.11 2021)
![UPDATE](assets/update_feature.png)

[Check Windows Insider Blog](https://blogs.windows.com/windows-insider/)

## After Update
![after update](assets/after_update.png)

----------




install WSL2
install Ubuntu
install Docker
check gpu working
