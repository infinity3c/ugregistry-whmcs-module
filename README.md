# ugregistry-whmcs-module
#### Infinity Computers and Communications Company (I3C) WHMCS Registrar Module built on top of the .UGRegistry JSON API

*************************************************************************
* .UGRegistry Module Plugin for .ug cctld domain registration, Management, Transfer solution.                                        
* Copyright (c) Infinity Computers and communications Company Limited. 
* All Rights Reserved.
   
* Version: 2.0                                                           
* Build Date: 17 Aug 2022    
   
## Installation
1) Upload the UgRegistry folder to this path <WHMCS_PATH>/modules/registrars/
2) You'll require a free license to run the .UG module, this can be got from visiting https://billing.i3c.co.ug/index.php/store/software-licensing/ugregistry after checkout, 
click on services then .UGRegistry to reveal the license.
3) Copy this license and paste it in your license.txt file in the UGRegistry Module you uploaded to your WHMCS (<WHMCS_PATH>/modules/registrars/UGRegistry) and save.
4) After adding the license, login to your WHMCS as Admin and go to Setup -> Domain Registrars
5) Activate the UGRegistry Module.
6) After Activation insert your API key and a name. This is got from your registrar account on https://registry.co.ug/api_keys 
7) Test if your module can be activated and works, if not contact our support at support@registry.co.ug /support@i3c.co.ug
8) In your WHMCS as Admin go to Setup -> Domain Pricing and change the Lookup Provider to UGRegistry and select the .UG ccTLDs you would like to sell on your store front and save.
9) Ensure to have enough credit on your .UG Registry Account to use your module in production. Or load credit using https://registry.co.ug/credit_deposits

#### Test Mode Environment
1) In order to use your module in Test Mode, login to your WHMCS as Admin and go to Setup -> Domain Registrars -> UGRegistry and click configure
2) Next tick checkbox on Test Mode and click on 'create one' link to create a .UG Sandbox account.
3) A sign in will pop up. Use username: registry-staging and password: E8u3BGgHkacX5qUu  to proceed.
4) Signup and create API Key that you are going to use in your WHMCS.
5) Send a request with subject 'SANDBOX CREDIT TOPUP' to support@registry.co.ug with your email account you used to signup above.
6) Please note, all domains created via sandbox are not submitted to the global .ug servers and will not be usable on the internet.
7) Lastly, if you are able to register a few domains within your WHMCS, uncheck the checkbox on Test Mode to go to production.

### Note:
●	The encrypted files UGRegistry.php and ApiClient.php should not be edited at all, otherwise the module will not work. If any changes are made accidentally or intentionally to these encrypted files, please replace them with the original files in the UGRegistry folder to avoid licence invalidity.

●	Each Licence is only permitted per server instance. i.e. You have to generate a new licence for every server that you install the UGRegistry module.

  
## Licence                                                                       
   This software is furnished under a license and may be used and copied 
   only  in  accordance  with  the  terms  of such  license and with the 
   inclusion of the above copyright notice.  This software  or any other 
   copies thereof may not be provided or otherwise made available to any 
   other person.  No title to and  ownership of the  software is  hereby 
   transferred.                                                          
                                                                         
   You may not reverse  engineer, decompile, defeat  license  encryption 
   mechanisms, or  disassemble this software product or software product 
   license. i3c may terminate this license if you don't comply with any 
   of the terms and conditions set forth in our end user license         
   agreement (https://i3c.co.ug/general-terms-of-use).                   
   In such event, licensee agrees to return licensor or destroy all copies
   of software upon termination of the license.               
   Furthermore it might lead to cancellation of all domain names created 
   Without any refund given.
   
## Support                                                                         
   Please contact support incase of any issues using this 
   Module.    
   Email: support@registry.co.ug                                         
   Website: https://i3c.co.ug
   *************************************************************************
  
