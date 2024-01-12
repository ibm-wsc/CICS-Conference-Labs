<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
<script src="./core-min.js"></script>
<script src="./md5-min.js"></script>
<script src="./wildfire-labs.js"></script>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KyZXEAg3QhqLMpG8r+8fhAXLRk2vvoC2f3B09zVXn8CA5QIVfZOJ3BCsw2P0p/We" crossorigin="anonymous">

## Welcome

Thank you for attending this Washington Systems Center(WSC) workshop. 

## Accessing the hands-on lab

Click [here](Lab Environment Connection Instructions.pdf){:target="_blank"} to read instructions for accessing the IBM systems from your workstation.

Click [here](https://github.com/ibm-wsc/zCONNEE-Wildfire-Workshop/blob/master/OpenAPI2/Important-Read%20Me.pdf) for important information regarding credentials for accessing z/OS. This document also contains information on 3270 Emulator (IBM Personal Communications) keyboard mappings for the **Enter** and **Clear** keys as well as direction on how to customize the 3270 Personal Communications keyboard for use with Mac keyboards.

## Lab Exercises and Presentations

Lab Exercises and Presentations have been posted at [https://github.com/ibm-wsc/CICS-Wildfire-Workshops/tree/main](https://github.com/ibm-wsc/CICS-Wildfire-Workshops/tree/main).

If you do not have two monitors, you may want to print the lab instructions prior to attending the workshop.

- [Introduction to the Java Workshop](https://github.com/ibm-wsc/CICS-Wildfire-Workshops/blob/main/CICS-Java%20Lab%20Exercises/L01-V61.01.zVA-JavaLabIntroduction.pdf).
- [CICS OGSi Program](https://github.com/ibm-wsc/CICS-Wildfire-Workshops/blob/main/CICS-Java%20Lab%20Exercises/L34-V61.01.zVA-SimpleOSGiProgramWithCICSExplorer.pdf) 
- [Using Servlets and JSPs in CICS](https://github.com/ibm-wsc/CICS-Wildfire-Workshops/blob/main/CICS-Java%20Lab%20Exercises/L70-V61.01.zVA-UsingServletsAndJspsWithCICS.pdf).
- [Servlet with LINK to CICS COBOL program](https://github.com/ibm-wsc/CICS-Wildfire-Workshops/blob/main/CICS-Java%20Lab%20Exercises/L72-V61.03.zVA-CICS-Java-Servlet-LINKtoCOBOLProgram.pdf).
- [JAX-RS and JSON](https://github.com/ibm-wsc/CICS-Wildfire-Workshops/blob/main/CICS-Java%20Lab%20Exercises/L92-V61.01.zVA-CICS-JSONusingJAX-RSnon-OSGi.pdf).
- [JAX-RS and JSON with LINK to CICS COBOL program](https://github.com/ibm-wsc/CICS-Wildfire-Workshops/blob/main/CICS-Java%20Lab%20Exercises/L93-V61.01.zVA-CICS-JSON-JAX-RS-non-OSGi-Application.pdf).
- [RESTful APIs with z/OS Connect](https://github.com/ibm-wsc/CICS-Wildfire-Workshops/blob/main/CICS-Java%20Lab%20Exercises/L97-V30.05.zVA-zosConnect-EE-BottomUp.pdf)).




**Please enter your email address used for registration to retrieve your unique log in details.**

<form onsubmit="return false;">
<div class="input-group mb-3 col-6">
<span class="input-group-text" id="basic-addon1">@</span>
<input type="email" class="form-control" placeholder="Registration Email" aria-label="Email" aria-describedby="basic-addon1" id="registration-email" maxlength="50" required oninput="validate();">
</div>
<div class="col-6">
<button id="btn-submit" class="btn btn-primary" type="submit" onclick="getLab(document.getElementById('registration-email').value)" disabled>Submit</button>
</div>
</form>
<div id="lab" class=".container .text-monospace">
<em>Note you will need a confirmed registration to access the lab.</em>
</div>

## Help 
Having trouble with labs? Send an email to [Steve Fowlkes](mailto: fowlkes@us.ibm.com) or [Leigh Compton](mailto: lcompton@us.ibm.com) for help.
