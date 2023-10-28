# OpenAPI Specification Files for 3GPP 5G Core Network (Release 18)

© 2023, 3GPP Organizational Partners (ARIB, ATIS, CCSA, ETSI, TSDSI, TTA, TTC). All rights reserved.

API version: **September 2023**  
Release status: **{+ Open +}**  
Other releases: [Rel-17 (Frozen)](https://forge.3gpp.org/rep/all/5G_APIs/tree/REL-17), [Rel-16 (Frozen)](https://forge.3gpp.org/rep/all/5G_APIs/tree/REL-16), [Rel-15 (Frozen)](https://forge.3gpp.org/rep/all/5G_APIs/tree/REL-15)


OpenAPI validation status:
[![pipeline status](https://forge.3gpp.org/rep/all/5G_APIs/badges/REL-18/pipeline.svg)](https://forge.3gpp.org/rep/all/5G_APIs/commits/REL-18)

#### Tools
* <a href="https://forge.3gpp.org/swagger/tools/parser.html">API Parser/Linter</a> to parse OpenAPI files with APIDevTools Swagger Parser/Validator and run a number of <a href="https://en.wikipedia.org/wiki/Lint_(software)" target="_blank">lint</a> rules to improve API quality
* <a href="https://forge.3gpp.org/swagger/tools/types.html">Data Type Finder</a> to find the impacted APIs due to a change on a given data type
* <a href="https://forge.3gpp.org/swagger/tools/versions.html">API Versions Overview</a> to show a comprehensive report of the versions of all APIs in the repository
* <a href="https://forge.3gpp.org/swagger/tools/headers.html?abnf=TS29500_CustomHeaders.abnf">ABNF</a> checker of 3GPP HTTP headers

The links below will open the Swagger Editor/UI and auto-load the OpenAPI YAML file of each Network Function (NF) API:

<!-- APIs -->
<!-- SWAGGER_EDITOR_VERSION = 3.18.0 -->

## NRF (NF Repository Function)
* NF Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29510_Nnrf_NFManagement.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29510_Nnrf_NFManagement.yaml))
* NF Discovery
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29510_Nnrf_NFDiscovery.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29510_Nnrf_NFDiscovery.yaml))
* Oauth2 Access Token Request
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29510_Nnrf_AccessToken.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29510_Nnrf_AccessToken.yaml))
* Bootstrapping
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29510_Nnrf_Bootstrapping.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29510_Nnrf_Bootstrapping.yaml))

## LMF (Location Management Function)
* Location
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29572_Nlmf_Location.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29572_Nlmf_Location.yaml))
* Broadcast
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29572_Nlmf_Broadcast.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29572_Nlmf_Broadcast.yaml))

## AMF (Access and Mobility Management Function)
* Communication
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29518_Namf_Communication.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29518_Namf_Communication.yaml))
* Event Exposure
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29518_Namf_EventExposure.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29518_Namf_EventExposure.yaml))
* Location
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29518_Namf_Location.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29518_Namf_Location.yaml))
* MT (Mobile-Terminated)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29518_Namf_MT.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29518_Namf_MT.yaml))
* MBS Communication
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29518_Namf_MBSCommunication.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29518_Namf_MBSCommunication.yaml))
* MBS Broadcast
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29518_Namf_MBSBroadcast.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29518_Namf_MBSBroadcast.yaml))

## SMF (Session Management Function)
* PDU Session
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29502_Nsmf_PDUSession.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29502_Nsmf_PDUSession.yaml))
([ABNF](https://forge.3gpp.org/swagger/tools/headers.html?abnf=TS29502_CustomHeaders.abnf))
* Event Exposure
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29508_Nsmf_EventExposure.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29508_Nsmf_EventExposure.yaml))
* NIDD (Non-IP Data Delivery)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29542_Nsmf_NIDD.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29542_Nsmf_NIDD.yaml))

## MB-SMF (Multicast/Broadcast Session Management Function)
* MBS Session
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29532_Nmbsmf_MBSSession.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29532_Nsmf_MBSSession.yaml))
* MBS TMGI
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29532_Nmbsmf_TMGI.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29532_Nsmf_TMG.yaml))

## MBSF (Multicast/Broadcast Service Function)
* MBS User Service
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29580_Nmbsf_MBSUserService.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29580_Nmbsf_MBSUserService.yaml))
* MBS User Data Ingest Session
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29580_Nmbsf_MBSUserDataIngestSession.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29580_Nmbsf_MBSUserDataIngestSession.yaml))

## MBSTF (Multicast/Broadcast Service Transport Function)
* MBS Distribution Session
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29581_Nmbstf_DistSession.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29581_Nmbstf_DistSession.yaml))

## MB (Multicast/Broadcast) User Services
* MBS User Service Announcement
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS26517_MBSUserServiceAnnouncement.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS26517_MBSUserServiceAnnouncement.yaml))
* MBS Object Manifest
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS26517_MBSObjectManifest.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS26517_MBSObjectManifest.yaml))

## UDM (Unified Data Management)
* Subscriber Data Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29503_Nudm_SDM.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29503_Nudm_SDM.yaml))
* UE Context Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29503_Nudm_UECM.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29503_Nudm_UECM.yaml))
* UE Authentication
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29503_Nudm_UEAU.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29503_Nudm_UEAU.yaml))
* Event Exposure
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29503_Nudm_EE.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29503_Nudm_EE.yaml))
* Parameter Provisioning
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29503_Nudm_PP.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29503_Nudm_PP.yaml))
* NIDD (Non-IP Data Delivery) Authorization
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29503_Nudm_NIDDAU.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29503_Nudm_NIDDAU.yaml))
* MT (Mobile-Terminated)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29503_Nudm_MT.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29503_Nudm_MT.yaml))
* SSAU (Service Specific Authorization)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29503_Nudm_SSAU.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29503_Nudm_SSAU.yaml))
* RSDS (Report SM Delivery Status)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29503_Nudm_RSDS.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29503_Nudm_RSDS.yaml))
* UEID (UE Identifier)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29503_Nudm_UEID.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29503_Nudm_UEID.yaml))

## UDR (Unified Data Repository)
* Data Repository
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29504_Nudr_DR.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29504_Nudr_DR.yaml))
([ABNF](https://forge.3gpp.org/swagger/tools/headers.html?abnf=TS29504_CustomHeaders.abnf))
  * Subscription Data
    ([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29505_Subscription_Data.yaml))
    ([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29505_Subscription_Data.yaml))
  * Policy Data
    ([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29519_Policy_Data.yaml))
    ([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29519_Policy_Data.yaml))
  * Exposure Data
    ([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29519_Exposure_Data.yaml))
    ([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29519_Exposure_Data.yaml))
  * Application Data
    ([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29519_Application_Data.yaml))
    ([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29519_Application_Data.yaml))
* Group ID Map
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29504_Nudr_GroupIDmap.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29504_Nudr_GroupIDmap.yaml))

## UDSF (Unstructured Data Storage Function)
* Data Repository
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29598_Nudsf_DataRepository.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29598_Nudsf_DataRepository.yaml))
* Timer
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29598_Nudsf_Timer.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29598_Nudsf_Timer.yaml))

## AUSF (Authentication Server Function)
* UE Authentication
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29509_Nausf_UEAuthentication.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29509_Nausf_UEAuthentication.yaml))
* SoR (Steering of Roaming) Protection
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29509_Nausf_SoRProtection.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29509_Nausf_SoRProtection.yaml))
* UPU (UE Parameter Update) Protection
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29509_Nausf_UPUProtection.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29509_Nausf_UPUProtection.yaml))

## NSSAAF (Network Slice-Specific and SNPN Authentication and Authorization Function)
* NSSAA
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29526_Nnssaaf_NSSAA.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29526_Nnssaaf_NSSAA.yaml))
* AIW
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29526_Nnssaaf_AIW.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29526_Nnssaaf_AIW.yaml))

## NSACF (Network Slice Admission Control)
* NSAC
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29536_Nnsacf_NSAC.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29536_Nnsacf_NSAC.yaml))
* SliceEventExposure
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29536_Nnsacf_SliceEventExposure.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29536_Nnsacf_SliceEventExposure.yaml))

## NSSF (Network Slice Selection Function)
* NSSAI Availability
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29531_Nnssf_NSSAIAvailability.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29531_Nnssf_NSSAIAvailability.yaml))
* NS Selection
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29531_Nnssf_NSSelection.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29531_Nnssf_NSSelection.yaml))

## SMSF (SMS Function)
* SM Service
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29540_Nsmsf_SMService.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29540_Nsmsf_SMService.yaml))

## 5G-EIR (5G Equipment Identity Register)
* Equipment Identity Check
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29511_N5g-eir_EquipmentIdentityCheck.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29511_N5g-eir_EquipmentIdentityCheck.yaml))

## NEF (Network Exposure Function)
* Packet Flow Description (PFD) Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29551_Nnef_PFDmanagement.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29551_Nnef_PFDmanagement.yaml))
* Session Management (SM) Context
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29541_Nnef_SMContext.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29541_Nnef_SMContext.yaml))
* Short Message (SM) Service
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29541_Nnef_SMService.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29541_Nnef_SMService.yaml))
* Event Exposure
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29591_Nnef_EventExposure.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29591_Nnef_EventExposure.yaml))
* Authentication
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29256_Nnef_Authentication.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29256_Nnef_Authentication.yaml))
* EAS Deployment
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29591_Nnef_EASDeployment.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29591_Nnef_EASDeployment.yaml))
* Traffic Influence Data
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29591_Nnef_TrafficInfluenceData.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29591_Nnef_TrafficInfluenceData.yaml))
* ECS Address
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29591_Nnef_ECSAddress.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29591_Nnef_ECSAddress.yaml))
* DNAI Mapping
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29591_Nnef_DNAIMapping.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29591_Nnef_DNAIMapping.yaml))

## PCF (Policy Control Function)
* Policy Authorization
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29514_Npcf_PolicyAuthorization.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29514_Npcf_PolicyAuthorization.yaml))
* Access and Mobility (AM) Policy Authorization
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29534_Npcf_AMPolicyAuthorization.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29534_Npcf_AMPolicyAuthorization.yaml))
* Access and Mobility (AM) Policy Control
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29507_Npcf_AMPolicyControl.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29507_Npcf_AMPolicyControl.yaml))
* Session Management (SM) Policy Control
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29512_Npcf_SMPolicyControl.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29512_Npcf_SMPolicyControl.yaml))
* Background Data Transfer (BDT) Policy Control
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29554_Npcf_BDTPolicyControl.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29554_Npcf_BDTPolicyControl.yaml))
* Policy Control Event Exposure
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29523_Npcf_EventExposure.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29523_Npcf_EventExposure.yaml))
* UE Policy Control
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29525_Npcf_UEPolicyControl.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29525_Npcf_UEPolicyControl.yaml))
* Multicast/Broadcast Policy Control
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29537_Npcf_MBSPolicyControl.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29537_Npcf_MBSPolicyControl.yaml))
* Multicast/Broadcast Policy Authorization
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29537_Npcf_MBSPolicyAuthorization.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29537_Npcf_MBSPolicyAuthorization.yaml))
* Planned Data Transfer with QoS (PDTQ) Policy Control
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29543_Npcf_PDTQPolicyControl.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&&yaml=TS29543_Npcf_PDTQPolicyControl.yaml))

## BSF (Binding Support Function)
* Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29521_Nbsf_Management.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29521_Nbsf_Management.yaml))

## NWDAF (Network Data Analytics Function)
* Events Subscription
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29520_Nnwdaf_EventsSubscription.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29520_Nnwdaf_EventsSubscription.yaml))
* Analytics Info
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29520_Nnwdaf_AnalyticsInfo.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29520_Nnwdaf_AnalyticsInfo.yaml))
* Data Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29520_Nnwdaf_DataManagement.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29520_Nnwdaf_DataManagement.yaml))
* MLModel Provision
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29520_Nnwdaf_MLModelProvision.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29520_Nnwdaf_MLModelProvision.yaml))
* MLModel Training
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29520_Nnwdaf_MLModelTraining.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29520_Nnwdaf_MLModelTraining.yaml))

## UPF (User Plane Function)
* Event Exposure
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29564_Nupf_EventExposure.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29564_Nupf_EventExposure.yaml))
* Get Private UE IP Address
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29564_Nupf_GetPrivateUEIPaddr.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29564_Nupf_GetPrivateUEIPaddr.yaml))

## HSS (Home Subscriber Server)
* UE Authentication
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29563_Nhss_UEAU.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29563_Nhss_UEAU.yaml))
* Subscriber Data Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29563_Nhss_SDM.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29563_Nhss_SDM.yaml))
* UE Context Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29563_Nhss_UECM.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29563_Nhss_UECM.yaml))
* Event Exposure
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29563_Nhss_EE.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29563_Nhss_EE.yaml))
* IMS UE Authentication
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29562_Nhss_imsUEAU.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29562_Nhss_imsUEAU.yaml))
* IMS Subscriber Data Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29562_Nhss_imsSDM.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29562_Nhss_imsSDM.yaml))
* IMS UE Context Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29562_Nhss_imsUECM.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29562_Nhss_imsUECM.yaml))
* GBA Subscriber Data Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29562_Nhss_gbaSDM.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29562_Nhss_gbaSDM.yaml))
* GBA UE Authentication
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29562_Nhss_gbaUEAU.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29562_Nhss_gbaUEAU.yaml))

## GBA BSF (GBA Bootstrapping Server Function)
* GBA Service
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29309_Nbsp_GBA.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29309_Nbsp_GBA.yaml))

## SOR-AF (Steering of Roaming Application Function)
* Steering of Roaming
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29550_Nsoraf_SOR.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29550_Nsoraf_SOR.yaml))

## SP-AF (Secured Packet Application Function)
* Secured Packet
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29544_Nspaf_SecuredPacket.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29544_Nspaf_SecuredPacket.yaml))

## AF (Application Function)
* Event Exposure
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29517_Naf_EventExposure.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29517_Naf_EventExposure.yaml))
* ProSe
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29557_Naf_ProSe.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29557_Naf_ProSe.yaml))
* Authentication
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29255_Naf_Authentication.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29255_Naf_Authentication.yaml))

## CHF (Charging Function)
* Spending Limit Control
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29594_Nchf_SpendingLimitControl.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29594_Nchf_SpendingLimitControl.yaml))
* Converged Charging
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS32291_Nchf_ConvergedCharging.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS32291_Nchf_ConvergedCharging.yaml))
* Offline-Only Charging
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS32291_Nchf_OfflineOnlyCharging.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS32291_Nchf_OfflineOnlyCharging.yaml))

## Common Data Types
* Common Data
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29571_CommonData.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29571_CommonData.yaml))

## SEPP N32 APIs
* Handshake (N32-c)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29573_N32_Handshake.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29573_N32_Handshake.yaml))
* Forwarding (N32-f)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29573_JOSEProtectedMessageForwarding.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29573_JOSEProtectedMessageForwarding.yaml))
* Telescopic FQDN Mapping
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29573_SeppTelescopicFqdnMapping.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29573_SeppTelescopicFqdnMapping.yaml))

## UCMF (UE Radio Capability Management Function)
* UE Radio Capability Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29673_Nucmf_UERCM.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29673_Nucmf_UERCM.yaml))
* Provisioning
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29675_Nucmf_Provisioning.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29675_Nucmf_Provisioning.yaml))

## MNPF (Mobile Number Portability Function)
* Number Portability Status
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29578_Nmnpf_NPStatus.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29578_Nmnpf_NPStatus.yaml))

## GMLC (Gateway Mobile Location Center)
* Location
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29515_Ngmlc_Location.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29515_Ngmlc_Location.yaml))

## EASDF (Edge Application Server Discovery Function)
* DNS Context
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29556_Neasdf_DNSContext.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29556_Neasdf_DNSContext.yaml))
* Baseline DNS Pattern
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29556_Neasdf_BaselineDNSPattern.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29556_Neasdf_BaselineDNSPattern.yaml))

## AAnF (AKMA Anchor Function)
* AKMA Anchor Service
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29535_Naanf_AKMA.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29535_Naanf_AKMA.yaml))

## 5G DDNMF (Inter-5G Direct Discovery Name Management Function)
* Discovery
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29555_N5g-ddnmf_Discovery.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29555_N5g-ddnmf_Discovery.yaml))

## TSCTSF (Time Sensitive Communication and Time Synchronization Function)
* Time Synchronization
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29565_Ntsctsf_TimeSynchronization.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29565_Ntsctsf_TimeSynchronization.yaml))
* QoS and TSC Assistance
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29565_Ntsctsf_QoSandTSCAssistance.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29565_Ntsctsf_QoSandTSCAssistance.yaml))
* ASTI
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29565_Ntsctsf_ASTI.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29565_Ntsctsf_ASTI.yaml))

## ADRF (Analytics Data Repository Function)
* Data Management 
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29575_Nadrf_DataManagement.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29575_Nadrf_DataManagement.yaml))
* ML Model Management 
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29575_Nadrf_MLModelManagement.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29575_Nadrf_MLModelManagement.yaml))

## MFAF (Messaging Framework Adaptor Function)
* 3GPP DCCF Adaptor (3DA) Data Management 
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29576_Nmfaf_3daDataManagement.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29576_Nmfaf_3daDataManagement.yaml))
* 3GPP Consumer Adaptor (3CA) Data Management 
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29576_Nmfaf_3caDataManagement.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29576_Nmfaf_3caDataManagement.yaml))

## Data Collection Application Function
* Common Data Types
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS26532_CommonData.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS26532_CommonData.yaml))
* Application Service Provider provisioning (R1)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS26532_Ndcaf_DataReportingProvisioning.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS26532_Ndcaf_DataReportingProvisioning.yaml))
* Data collection client configuration and reporting (R2, R3, R4)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS26532_Ndcaf_DataReporting.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS26532_Ndcaf_DataReporting.yaml))

## Data Collection Coordination Function (DCCF)
* Data Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29574_Ndccf_DataManagement.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29574_Ndccf_DataManagement.yaml))
* Context Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29574_Ndccf_ContextManagement.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29574_Ndccf_ContextManagement.yaml))

## IP-SM-GW (IP Short Message Gateway)
* SM Service
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29577_Nipsmgw_SMService.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29577_Nipsmgw_SMService.yaml))

## SMS Router
* SM Service
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29577_Nrouter_SMService.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29577_Nrouter_SMService.yaml))

## SMS-IWMSC (Interworking MSC for Short Message Service)
* SM Service
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29579_Niwmsc_SMService.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29579_Niwmsc_SMService.yaml))

## PKMF (ProSe Key Management Service)
* Key Request Service
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29559_Npkmf_PKMFKeyRequest.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29559_Npkmf_PKMFKeyRequest.yaml))
* Resolve Remote User Id
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29559_Npkmf_UserId.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29559_Npkmf_UserId.yaml))

## PANF (ProSe Anchor Function)
* Prose Key Service
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29553_Npanf_ProseKey.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29553_Npanf_ProseKey.yaml))
* Resolve Remote User Id
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29553_Npanf_ResolveRemoteUserId.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29553_Npanf_ResolveRemoteUserId.yaml))

# Northbound and Application Layer APIs
## CAPIF (Common API Framework)
* Discover Service
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_Discover_Service_API.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_Discover_Service_API.yaml))
* Publish Service
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_Publish_Service_API.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_Publish_Service_API.yaml))
* Events
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_Events_API.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_Events_API.yaml))
* API Invoker Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_API_Invoker_Management_API.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_API_Invoker_Management_API.yaml))
* Security
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_Security_API.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_Security_API.yaml))
* Access Control Policy
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_Access_Control_Policy_API.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_Access_Control_Policy_API.yaml))
* Logging API Invocation
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_Logging_API_Invocation_API.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_Logging_API_Invocation_API.yaml))
* Auditing
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_Auditing_API.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_Auditing_API.yaml))
* AEF Authentication
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29222_AEF_Security_API.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29222_AEF_Security_API.yaml))
* API Provider Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_API_Provider_Management_API.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_API_Provider_Management_API.yaml))
* Routing Information
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_Routing_Info_API.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_Routing_Info_API.yaml))

## SCEF (Service Capability Exposure Function)
>**Note:**
These APIs are not part of the 5G Core Network; these APIs are exposed by the 4G SCEF to the SCS/AS
* Event Monitoring
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_MonitoringEvent.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_MonitoringEvent.yaml))
* Resource Management of Background Data Transfer (BDT)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_ResourceManagementOfBdt.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_ResourceManagementOfBdt.yaml))
* Chargeable Party
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_ChargeableParty.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_ChargeableParty.yaml))
* Non-IP Data Delivery (NIDD)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_NIDD.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_NIDD.yaml))
* Device Triggering
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_DeviceTriggering.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_DeviceTriggering.yaml))
* Group Message Delivery via MBMS by MB2
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_GMDviaMBMSbyMB2.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_GMDviaMBMSbyMB2.yaml))
* Group Message Delivery via MBMS by xMB
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_GMDviaMBMSbyxMB.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_GMDviaMBMSbyxMB.yaml))
* Network Status Reporting
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_ReportingNetworkStatus.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_ReportingNetworkStatus.yaml))
* Communication Patterns (CP) Parameters Provisioning
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_CpProvisioning.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_CpProvisioning.yaml))
* Packet Flow Description (PFD) Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_PfdManagement.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_PfdManagement.yaml))
* Enhanced Coverage Restriction Control
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_ECRControl.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_ECRControl.yaml))
* Network Parameter Configuration
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_NpConfiguration.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_NpConfiguration.yaml))
* Application Server (AS) Session with QoS
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_AsSessionWithQoS.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_AsSessionWithQoS.yaml))
* MSISDN-less Mobile-Originated SMS
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_MsisdnLessMoSms.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_MsisdnLessMoSms.yaml))
* RACS (Radio Capability Signaling) Parameter Provisioning
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_RacsParameterProvisioning.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_RacsParameterProvisioning.yaml))
* Common Data
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_CommonData.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_CommonData.yaml))

## NEF (Network Exposure Function)
* Traffic Influence
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_TrafficInfluence.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_TrafficInfluence.yaml))
* NIDD (Non-IP Data Delivery) Configuration Trigger
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_NIDDConfigurationTrigger.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_NIDDConfigurationTrigger.yaml))
* 5G LAN Parameter Provision
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_5GLANParameterProvision.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_5GLANParameterProvision.yaml))
* Applying BDT Policy
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_ApplyingBdtPolicy.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_ApplyingBdtPolicy.yaml))
* IPTV Configuration
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_IPTVConfiguration.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_IPTVConfiguration.yaml))
* Analytics Exposure
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_AnalyticsExposure.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_AnalyticsExposure.yaml))
* LPI (Location Privacy Indicator) Parameter Provision
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_LpiParameterProvision.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_LpiParameterProvision.yaml))
* Service Parameter
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_ServiceParameter.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_ServiceParameter.yaml))
* ACS Parameter Provision
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_ACSParameterProvision.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_ACSParameterProvision.yaml))
* MO LCS Notify
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_MoLcsNotify.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_MoLcsNotify.yaml))
* AKMA
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_AKMA.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_AKMA.yaml))
* Time Sync Exposure
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_TimeSyncExposure.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_TimeSyncExposure.yaml))
* ECS Address Provision
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_EcsAddressProvision.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_EcsAddressProvision.yaml))
* AM Policy Authorization
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_AMPolicyAuthorization.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_AMPolicyAuthorization.yaml))
* AM Influence
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_AMInfluence.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_AMInfluence.yaml))
* MBS TMGI
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_MBSTMGI.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_MBSTMGI.yaml))
* MBS Session
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_MBSSession.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_MBSSession.yaml))
* EAS Deployment
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_EASDeployment.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_EASDeployment.yaml))
* ASTI
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_ASTI.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_ASTI.yaml))
* Data Reporting
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_DataReporting.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_DataReporting.yaml))
* Data Reporing Provisioning
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_DataReportingProvisioning.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_DataReportingProvisioning.yaml))
* UE Identifier
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_UEId.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_UEId.yaml))
* MBS User Service
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_MBSUserService.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_MBSUserService.yaml))
* MBS User Data Ingest Session
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_MBSUserDataIngestSession.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_MBSUserDataIngestSession.yaml))
* Media Streaming Event Exposure
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_MSEventExposure.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_MSEventExposure.yaml))
* MBS Group Message Delivery
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_MBSGroupMsgDelivery.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_MBSGroupMsgDelivery.yaml))
* DNAI Mapping
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_DNAIMapping.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_DNAIMapping.yaml))
* PDTQ Policy Negotiation
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_PDTQPolicyNegotiation.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_PDTQPolicyNegotiation.yaml))
* Member UE Selection Assistance
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_MemberUESelectionAssistance.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_MemberUESelectionAssistance.yaml))
* Group Parameters Provisioning
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_GroupParametersProvisioning.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_GroupParametersProvisioning.yaml))
* Slice Parameters Provisioning
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_SliceParamProvision.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_SliceParamProvision.yaml))

## VAE (V2X Application Enabler)
* V2X Message Delivery
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29486_VAE_MessageDelivery.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29486_VAE_MessageDelivery.yaml))
* File Distribution
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29486_VAE_FileDistribution.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29486_VAE_FileDistribution.yaml))
* Application Requirement
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29486_VAE_ApplicationRequirement.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29486_VAE_ApplicationRequirement.yaml))
* Dynamic Group
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29486_VAE_DynamicGroup.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29486_VAE_DynamicGroup.yaml))
* Service Continuity
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29486_VAE_ServiceContinuity.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29486_VAE_ServiceContinuity.yaml))
* HD Map Dynamic Information
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29486_VAE_HDMapDynamicInfo.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29486_VAE_HDMapDynamicInfo.yaml))
* Session Oriented Service
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29486_VAE_SessionOrientedService.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29486_VAE_SessionOrientedService.yaml))
* V2V Config Requirement
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29486_VAE_V2VConfigRequirement.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29486_VAE_V2VConfigRequirement.yaml))
* PC5 Provisioning Requirement
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29486_VAE_PC5ProvisioningRequirement.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29486_VAE_PC5ProvisioningRequirement.yaml))

## SEAL (Service Enabler Architecture Layer)
* Network Resource Adaptation
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29549_SS_NetworkResourceAdaptation.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29549_SS_NetworkResourceAdaptation.yaml))
* Network Resource Monitoring
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29549_SS_NetworkResourceMonitoring.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29549_SS_NetworkResourceMonitoring.yaml))
* Network Slice Adaptation
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29549_SS_NetworkSliceAdaptation.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29549_SS_NetworkSliceAdaptation.yaml))
* User Profile Retrieval
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29549_SS_UserProfileRetrieval.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29549_SS_UserProfileRetrieval.yaml))
* Events
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29549_SS_Events.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29549_SS_Events.yaml))
* Group Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29549_SS_GroupManagement.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29549_SS_GroupManagement.yaml))
* Location Reporting
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29549_SS_LocationReporting.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29549_SS_LocationReporting.yaml))
* Location Area Information Retrieval
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29549_SS_LocationAreaInfoRetrieval.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29549_SS_LocationAreaInfoRetrieval.yaml))
* Key Information Retrieval
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29549_SS_KeyInfoRetrieval.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29549_SS_KeyInfoRetrieval.yaml))
* VAL Service Data Retrieval
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29549_SS_VALServiceData.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29549_SS_VALServiceData.yaml))
* VAL Service Area Configuration
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29549_SS_VALServiceAreaConfiguration.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29549_SS_VALServiceAreaConfiguration.yaml))
* SEALDD Data Transmission
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29548_SDD_Transmission.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29548_SDD_Transmission.yaml))
* SEALDD Context Relocation
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29548_SDD_DDContext.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29548_SDD_DDContext.yaml))
* SEALDD Transmission Quality Measurement
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29548_SDD_TransmissionQualityMeasurement.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29548_SDD_TransmissionQualityMeasurement.yaml))

## EDGEAPP (Enabling Edge Applications)
* EAS Registration
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29558_Eees_EASRegistration.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29558_Eees_EASRegistration.yaml))
* UE Location
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29558_Eees_UELocation.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29558_Eees_UELocation.yaml))
* UE Identifier
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29558_Eees_UEIdentifier.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29558_Eees_UEIdentifier.yaml))
* Application Client Information
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29558_Eees_AppClientInformation.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29558_Eees_AppClientInformation.yaml))
* ACR Management Event
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29558_Eees_ACRManagementEvent.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29558_Eees_ACRManagementEvent.yaml))
* Session with QoS
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29558_Eees_SessionWithQoS.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29558_Eees_SessionWithQoS.yaml))
* EEC Context Relocation
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29558_Eees_EECContextRelocation.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29558_Eees_EECContextRelocation.yaml))
* EEL Managed ACR
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29558_Eees_EELManagedACR.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29558_Eees_EELManagedACR.yaml))
* ACR Status Update
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29558_Eees_ACRStatusUpdate.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29558_Eees_ACRStatusUpdate.yaml))
* EES Registration
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29558_Eecs_EESRegistration.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29558_Eecs_EESRegistration.yaml))
* Target EES Discovery
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29558_Eecs_TargetEESDiscovery.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29558_Eecs_TargetEESDiscovery.yaml))
* EEC Registration
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS24558_Eees_EECRegistration.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS24558_Eees_EECRegistration.yaml))
* ECS Service Provisioning
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS24558_Eecs_ServiceProvisioning.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS24558_Eecs_ServiceProvisioning.yaml))
* EAS Discovery
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS24558_Eees_EASDiscovery.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS24558_Eees_EASDiscovery.yaml))
* EES ACR Events
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS24558_Eees_ACREvents.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS24558_Eees_ACREvents.yaml))
* EES App Context Relocation
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS24558_Eees_AppContextRelocation.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS24558_Eees_AppContextRelocation.yaml))
* EES ACR Parameters Information
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29558_Eees_ACRParameterInformation.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29558_Eees_ACRParameterInformation.yaml))
* EES Common EAS Announcement
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29558_Eees_CommonEASAnnouncement.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29558_Eees_CommonEASAnnouncement.yaml))
* CAS Selected EES
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29558_Ecas_SelectedEES.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29558_Ecas_SelectedEES.yaml))

## UAS Application Enabler (UAE) Server
* C2 Operation Mode Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29257_UAE_C2OperationModeManagement.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29257_UAE_C2OperationModeManagement.yaml))
* Real-time UAV Status
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29257_UAE_RealtimeUAVStatus.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29257_UAE_RealtimeUAVStatus.yaml))
* USS Change Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29257_UAE_ChangeUSSManagement.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29257_UAE_ChangeUSSManagement.yaml))
* DAA Support
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29257_UAE_DAASupport.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29257_UAE_DAASupport.yaml))

## 5GMARCH (Enabling MSGin5G Service)
* AS Registration
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29538_MSGS_ASRegistration.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29538_MSGS_ASRegistration.yaml))
* MSGin5G Server Message Delivery
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29538_MSGS_MSGDelivery.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29538_MSGS_MSGDelivery.yaml))
* L3G Message Delivery
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29538_MSGG_L3GDelivery.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29538_MSGG_L3GDelivery.yaml))
* N3G Message Delivery
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29538_MSGG_N3GDelivery.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29538_MSGG_N3GDelivery.yaml))
* Broadcast Message Delivery
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29538_MSGG_BGDelivery.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29538_MSGG_BGDelivery.yaml))

## PINAPP (Personal IoT Network Application)
* PINServer PAS Registration
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29583_Ppinserver_ASRegistration.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29583_Ppinserver_ASRegistration.yaml))

# 5G Media Streaming (5GMS) TS 26.512
>**Note:**
The APIs at reference points M1 and M5 are exposed by the 5GMS AF.
* Common Data Types
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS26512_CommonData.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS26512_CommonData.yaml))

## Provisioning (M1)
* Provisioning Sessions
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS26512_M1_ProvisioningSessions.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS26512_M1_ProvisioningSessions.yaml))
* Server Certificates Provisioning
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS26512_M1_ServerCertificatesProvisioning.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS26512_M1_ServerCertificatesProvisioning.yaml))
* Content Preparation Templates Provisioning
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS26512_M1_ContentPreparationTemplatesProvisioning.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS26512_M1_ContentPreparationTemplatesProvisioning.yaml))
* Content Protocols Discovery
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS26512_M1_ContentProtocolsDiscovery.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS26512_M1_ContentProtocolsDiscovery.yaml))
* Content Hosting Provisioning
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS26512_M1_ContentHostingProvisioning.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS26512_M1_ContentHostingProvisioning.yaml))
* Consumption Reporting Provisioning
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS26512_M1_ConsumptionReportingProvisioning.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS26512_M1_ConsumptionReportingProvisioning.yaml))
* Metrics Reporting Provisioning
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS26512_M1_MetricsReportingProvisioning.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS26512_M1_MetricsReportingProvisioning.yaml))
* Policy Templates Provisioning
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS26512_M1_PolicyTemplatesProvisioning.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS26512_M1_PolicyTemplatesProvisioning.yaml))
* Edge Resources Provisioning
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS26512_M1_EdgeResourcesProvisioning.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS26512_M1_EdgeResourcesProvisioning.yaml))
* Event Data Processing Provisioning
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS26512_M1_EventDataProcessingProvisioning.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS26512_M1_EventDataProcessingProvisioning.yaml))

## Media Session Handling (M5)
* Service Access Information
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS26512_M5_ServiceAccessInformation.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS26512_M5_ServiceAccessInformation.yaml))
* Consumption Reporting
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS26512_M5_ConsumptionReporting.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS26512_M5_ConsumptionReporting.yaml))
* Metrics Reporting
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS26512_M5_MetricsReporting.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS26512_M5_MetricsReporting.yaml))
* Dynamic Policies
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS26512_M5_DynamicPolicies.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS26512_M5_DynamicPolicies.yaml))
* Network Assistance
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS26512_M5_NetworkAssistance.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS26512_M5_NetworkAssistance.yaml))

## Data Reporting
* 5GMS AS (R4)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS26512_R4_DataReporting.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS26512_R4_DataReporting.yaml))

# 3GPP SA5 models and MnS OpenAPI definitions
## Network Resource Models (NRM)
* Generic NRM (TS 28.623)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS28623_GenericNrm.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS28623_GenericNrm.yaml))
* Common NRM definitions (TS 28.623)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS28623_ComDefs.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS28623_ComDefs.yaml))
* NR NRM (TS 28.541)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS28541_NrNrm.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS28541_NrNrm.yaml))
* 5GC NRM (TS 28.541)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS28541_5GcNrm.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS28541_5GcNrm.yaml))
* Slice NRM (TS 28.541)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS28541_SliceNrm.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS28541_SliceNrm.yaml))
* Communication Service Assurance NRM (TS 28.536)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS28536_CoslaNrm.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS28536_CoslaNrm.yaml))
* MDA NRM (TS 28.104)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS28104_MdaNrm.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS28104_MdaNrn.yaml))
* MDA Report NRM (TS 28.104)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS28104_MdaReport.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS28104_MdaReport.yaml))
* AI/ML NRM (TS 28.105)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS28105_AiMlNrm.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS28105_AiMlNrm.yaml))
* Intent NRM (TS 28.312)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS28312_IntentNrm.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS28312_IntentNrm.yaml))
* Intent Expectations (TS 28.312)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS28312_IntentExpectations.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS28312_IntentExpectations.yaml))
* Edge NRM (TS 28.538)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS28538_EdgeNrm.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS28538_EdgeNrm.yaml))

## Management Services (MnS)
* Provisioning MnS (TS 28.532)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS28532_ProvMnS.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS28532_ProvMnS.yaml))
* Fault Supervision MnS (TS 28.532)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS28532_FaultMnS.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS28532_FaultMnS.yaml))
* Performance Measurement Job Control MnS (28.550)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS28550_PerfMeasJobCtrlMnS.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS28550_PerfMeasJobCtrlMnS.yaml))
* File Data Reporting MnS (TS 28.532)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS28532_FileDataReportingMnS.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS28532_FileDataReportingMnS.yaml))
* Performance Threshold Monitoring MnS (TS 28.532)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS28532_PerfMnS.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS28532_PerfMnS.yaml))
* Heartbeat Notifications (TS 28.532)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS28532_HeartbeatNtf.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS28532_HeartbeatNtf.yaml))
* Streaming Data Reporting MnS (TS 28.532)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS28532_StreamingDataMnS.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS28532_StreamingDataMnS.yaml))
