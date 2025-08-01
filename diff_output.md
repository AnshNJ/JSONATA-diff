# Diff Report

---

## Table of Contents

- **Constants**
  - [ybppAXML](#ybppaxml)
  - [yblIbmAuth](#yblibmauth)
  - [yblIbmAuthXML](#yblibmauthxml)
  - [PLCallbackURL](#plcallbackurl)
- **Plugin**
  - [plugLogger](#pluglogger)
- **Upstream**
  - [ybpp_newgenDisconnectPl](#ybpp-newgendisconnectpl)
  - [yb_checkPincode](#yb-checkpincode)
  - [ybpp_cibilRequestPl](#ybpp-cibilrequestpl)
- **Api Rule**
  - [/atomic/checkPincodePl](#-atomic-checkpincodepl)

---

## Constants

### 🟡 Changed Objects

<details><summary><b>ybppAXML</b></summary>

**Field Changed:** <code>updatedAt</code>

- Old:   <code>"2025-07-21T09:27:13.469Z"</code>
- New:   <code>"2025-07-29T09:11:40.691Z"</code>

**Field Added:** <code>value.sa-id</code>

<code>"hRXbmswo3sfKmhSFDkXucUvDUPJnfPNv"</code>


</details>
<details><summary><b>yblIbmAuth</b></summary>

**Field Changed:** <code>updatedAt</code>

- Old:   <code>"2025-07-21T09:27:14.071Z"</code>
- New:   <code>"2025-07-29T09:11:41.602Z"</code>

**Field Added:** <code>value.X-IBM-Client-Secret</code>

<code>"fa1268c1d81a62bfaa0e8fc74f783fef"</code>

**Field Added:** <code>value.X-IBM-Client-Id</code>

<code>"cbc4185d-e1af-45ee-9e72-5baddc601e39"</code>

**Field Added:** <code>value.sa-id</code>

<code>"hRXbmswo3sfKmhSFDkXucUvDUPJnfPNv"</code>


</details>
<details><summary><b>yblIbmAuthXML</b></summary>

**Field Changed:** <code>updatedAt</code>

- Old:   <code>"2025-07-21T09:27:13.537Z"</code>
- New:   <code>"2025-07-29T09:11:41.941Z"</code>

**Field Added:** <code>value.X-IBM-Client-Secret</code>

<code>"fa1268c1d81a62bfaa0e8fc74f783fef"</code>

**Field Added:** <code>value.X-IBM-Client-Id</code>

<code>"cbc4185d-e1af-45ee-9e72-5baddc601e39"</code>

**Field Added:** <code>value.sa-id</code>

<code>"hRXbmswo3sfKmhSFDkXucUvDUPJnfPNv"</code>


</details>
<details><summary><b>PLCallbackURL</b></summary>

**Field Changed:** 
<code>jsonataExpression</code>

```diff
 {
   "PSB": ["https://staging-api.paisabazaar.com/common/v1/partner/65/application/callback"],
   "YBL": ["https://example.com/callback"],
   "PTM": [
     "https://example.com/callback",
     "https://partners-stage.lending.paytm.com/v2/lenders/ybl/pl/distribution/mandate/callback",
     "https://partners-stage.lending.paytm.com/v2/lenders/ybl/pl/distribution/esign/callback",
     "https://partners-stage.lending.paytm.com/v2/lenders/ybl/pl/distribution/kyc/vcip/validation/callback",
     "https://partners-stage.lending.paytm.com/v2/lenders/ybl/pl/distribution/kyc/ekyc/validation/callback",
-    "https://webhook.site/5f33155a-ac8b-465d-a1c1-8c7f2a3bad91"
+    "https://webhook.site/5f33155a-ac8b-465d-a1c1-8c7f2a3bad912"
   ]
 }
```

**Field Changed:** <code>updatedAt</code>

- Old:   <code>"2025-07-29T19:16:49.595Z"</code>
- New:   <code>"2025-07-31T15:05:05.116Z"</code>

**Field Changed:** <code>value.PTM[5]</code>

- Old:   <code>"https://webhook.site/5f33155a-ac8b-465d-a1c1-8c7f2a3bad91"</code>
- New:   <code>"https://webhook.site/5f33155a-ac8b-465d-a1c1-8c7f2a3bad912"</code>


</details>

## Plugin

### 🟡 Changed Objects

<details><summary><b>plugLogger</b></summary>

**Field Changed:** <code>updatedAt</code>

- Old:   <code>"2025-07-29T09:11:42.486Z"</code>
- New:   <code>"2025-07-29T09:14:37.841Z"</code>

**Field Added:** <code>uiProps</code>

<code>{
  "urlCurl": "curl https://nca-uat.partner.yesbank.in/nca/internal/ppLogger  -X POST  -H 'Content-Type: application/json'  -d '{\"name\":\"\",\"upstreamBody\":{},\"basicDetails\":{},\"headers\":{},\"requestBody\":{},\"filterParams\":[\"\"]}'"
}</code>


</details>

## Upstream

### 🟡 Changed Objects

<details><summary><b>ybpp_newgenDisconnectPl</b></summary>

**Field Changed:** <code>updatedAt</code>

- Old:   <code>"2025-07-29T09:12:03.902Z"</code>
- New:   <code>"2025-07-29T09:14:52.211Z"</code>

**Field Added:** <code>uiProps</code>

<code>{
  "gatewayCurl": "curl http://localhost:8000/vendors/67e3b95a-d9bf-4678-a820-a5d1aa516de2  -X POST  -H 'Content-Type: application/json'  -H 'X-IBM-Client-ID: '  -H 'X-IBM-Client-Secret: '  -H 'sa-id: <AuthToken>'  -d '{}'",
  "urlCurl": "curl https://universeuat.yesbank.in/app/dpu/OD_AO_REST/v1/ExecuteAPI  -X POST  -H 'Content-Type: application/json'  -H 'X-IBM-Client-ID: '  -H 'X-IBM-Client-Secret: '  -d '{}'"
}</code>


</details>
<details><summary><b>yb_checkPincode</b></summary>

**Field Changed:** <code>updatedAt</code>

- Old:   <code>"2025-07-29T09:12:01.629Z"</code>
- New:   <code>"2025-07-29T11:37:56.349Z"</code>

**Field Added:** <code>uiProps</code>

<code>{
  "gatewayCurl": "curl http://localhost:8000/vendors/408af3a8-1e92-4265-a9b8-acf5db0b7bb8  -X POST  -H 'Content-Type: application/json'  -H 'sa-id: <AuthToken>'  -d '{}'",
  "urlCurl": "curl https://webhook.site/#!/view/9b0e3dbf-12f4-45b8-8fde-df7aa79b16b6  -X POST  -H 'Content-Type: application/json'  -d '{}'"
}</code>


</details>
<details><summary><b>ybpp_cibilRequestPl</b></summary>

**Field Changed:** <code>updatedAt</code>

- Old:   <code>"2025-07-29T09:12:07.827Z"</code>
- New:   <code>"2025-07-29T11:33:56.705Z"</code>

**Field Added:** <code>uiProps</code>

<code>{
  "gatewayCurl": "curl http://localhost:8000/vendors/416aaf8f-8dae-4f1e-94c8-b75f28f42d40  -X POST  -H 'Content-Type: text/xml'  -H 'X-IBM-Client-ID: '  -H 'X-IBM-Client-Secret: '  -H 'geoLat: '  -H 'geoLong: '  -H 'sa-id: <AuthToken>'  -d '{}'",
  "urlCurl": "curl https://universeuat.yesbank.in/app/dpu/WS/ElinkInsertRequest/v1  -X POST  -H 'Content-Type: text/xml'  -H 'X-IBM-Client-ID: '  -H 'X-IBM-Client-Secret: '  -H 'geoLat: '  -H 'geoLong: '  -d '{}'"
}</code>


</details>

## Api Rule

### 🟡 Changed Objects

<details><summary><b>/atomic/checkPincodePl</b></summary>

**Field Changed:** <code>flows[0].priority</code>

- Old:   <code>1</code>
- New:   <code>-1</code>

**Field Changed:** <code>flows[1].priority</code>

- Old:   <code>-1</code>
- New:   <code>1</code>

**Field Changed:** <code>flows[1].upstreams[0].skipExecution.allowSkip</code>

- Old:   <code>false</code>
- New:   <code>true</code>

**Field Changed:** 
<code>flows[1].upstreams[0].skipExecution.jsonataExpression</code>

```diff
+true
```

**Field Changed:** 
<code>flows[1].upstreams[1].outputMapping[0].jsonataExpression</code>

```diff
 {
   "result": {
     "code": 0,
-    "message": "Pincode 400701 is serviceable for product code PL",
-    "pinCode": "400701",
+    "message": "Pincode 400702 is serviceable for product code PL",
+    "pinCode": "400702",
     "state": "Maharashtra",
     "stateShort": "",
     "city": "",
     "district": "Thane",
     "region": "",
     "stateCode": 2,
     "cityCode": 400,
     "regionCode": "",
     "stdCode": "",
     "branchCode": "",
     "hubLocation": "",
     "icl_ocl": "",
     "idanti": "",
     "policy": "",
     "upi": "",
     "pq_yf_bundle_bb_ib": "",
     "branchDesc": "Mumbai",
     "stateTuef": "27"
   }
 }
```

**Field Changed:** <code>updatedAt</code>

- Old:   <code>"2025-07-29T09:12:20.419Z"</code>
- New:   <code>"2025-07-31T15:45:08.997Z"</code>


</details>

