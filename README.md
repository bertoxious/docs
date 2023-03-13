# docs

# A-Connect
A-Connect , a complete solution for the HMIS to connect with ABDM


**_Using NDHM HIU and Tracelyfe as an HIP_**

<details>
    <summary>Create consent from NDHM HIU web console</summary>
<p>
</p>
</details>

<details>
    <summary>Grant that Consent from the ABHA SBX App</summary>
<p>
</p>
</details>

<details>
    <summary>Create consent from NDHM HIU web console</summary>
<p>
</p>
</details>
<details>
    <summary>Callback from ABDM
    </summary>
<p>
```url 
https://gatew/v0.5/consents/hip/notify
```
</p>
</details>
<details>
    <summary>HIP Will respond to the notify call</summary>
<p>
```url
https://dev.abdm.gov.in/gateway/v0.5/consents/hip/on-notify
```
</p>
</details>
<details>
    <summary>ABDM will make a call to HIP for health information Request</summary>
<p>
```url
{{HIP_URL}}/v0.5/health-information/hip/request
```
</p>
</details>
<details>
    <summary>HIP will respond to ABDM with an on-request</summary>
<p>
```url
https://dev.abdm.gov.in/gateway/v0.5/health-information/hip/on-request
```
</p>
</details>
<details>
    <summary>HIP will send data on the data push url</summary>
<p>
The data push url will be the url obtained in the v0.5/health-information/hip/request
</p>
</details>
<details>
    <summary>After successful data transfer we can see the data on the NDHM HIU web console</summary>
<p>
</p>
</details>


