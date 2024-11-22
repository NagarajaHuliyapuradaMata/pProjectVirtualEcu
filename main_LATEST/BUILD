load(
      "@rules_cc//cc:defs.bzl"
   ,  "cc_library"
   ,  "cc_binary"
)

cc_library(
      name = "common"
   ,  hdrs = [
            "source/common/TypesStd.hpp"
      ]
   ,  includes   = ["./source/common"]
   ,  visibility = ["//visibility:public"]
)

cc_library(
      name = "aapFunctionalCluster_CommunicationManagement"
   ,  srcs = ["source/aapFunctionalCluster_CommunicationManagement/aapFunctionalCluster_CommunicationManagement.cpp"]
#  ,  deps = ["//repo_projects/pProjectVirtualEcu/main_LATEST:SwcServiceEcuM"]
   ,  hdrs = [
            "source/aapFunctionalCluster_CommunicationManagement/interface_CommunicationManagement_VerificationStatusConfigurationByDataId.hpp"
         ,  "source/aapFunctionalCluster_CommunicationManagement/interface_CommunicationManagement_VerificationStatusConfigurationByFreshnessId.hpp"
         ,  "source/aapFunctionalCluster_CommunicationManagement/interface_CommunicationManagement_VerificationStatus.hpp"
      ]
   ,  includes   = ["./source/aapFunctionalCluster_CommunicationManagement"]
   ,  visibility = ["//visibility:public"]
)

cc_library(
      name = "aapFunctionalCluster_Core"
   ,  srcs = ["source/aapFunctionalCluster_Core/aapFunctionalCluster_Core.cpp"]
#  ,  deps = ["//repo_projects/pProjectVirtualEcu/main_LATEST:SwcServiceEcuM"]
   ,  hdrs = [
            "source/aapFunctionalCluster_Core/interface_Core.hpp"
      ]
   ,  includes   = ["./source/aapFunctionalCluster_Core"]
   ,  visibility = ["//visibility:public"]
)

cc_library(
      name = "aapFunctionalCluster_Cryptography"
   ,  srcs = ["source/aapFunctionalCluster_Cryptography/aapFunctionalCluster_Cryptography.cpp"]
#  ,  deps = ["//repo_projects/pProjectVirtualEcu/main_LATEST:SwcServiceEcuM"]
   ,  hdrs = [
            "source/aapFunctionalCluster_Cryptography/interface_Cryptography_AuthCipherCtx.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_BlockService.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_Certificate.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_CertSignRequest.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_CryptoContext.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_CryptoPrimitiveId.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_CryptoProvider.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_CryptoService.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_DecryptorPrivateCtx.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_DigestService.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_EncryptorPrivateCtx.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_ExtensionService.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_HashFunctionCtx.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_IO.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_KeyAgreementPrivateCtx.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_KeyDecapsulatorPrivateCtx.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_KeyDerivationFunctionCtx.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_KeyEncapsulatorPublicCtx.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_KeySlot.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_KeyStorageProvider.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_MessageAuthnCodeCtx.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_MsgRecoveryPublicCtx.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_PrivateKey.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_RandomGeneratorCtx.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_Serializable.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_SigEncodePrivateCtx.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_SignatureService.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_SignerPrivateCtx.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_StreamCipherCtx.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_SymmetricBlockCipherCtx.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_SymmetricKey.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_SymmetricKeyWrapperCtx.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_UpdatesObserver.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_VerifierPublicCtx.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_VolatileTrustedContainer.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_X509CustomExtensionsParser.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_X509DN.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_X509Provider.hpp"
         ,  "source/aapFunctionalCluster_Cryptography/interface_Cryptography_X509PublicKeyInfo.hpp"
      ]
   ,  includes   = ["./source/aapFunctionalCluster_Cryptography"]
   ,  visibility = ["//visibility:public"]
)

cc_library(
      name = "aapFunctionalCluster_DiagnosticManagement"
   ,  srcs = ["source/aapFunctionalCluster_DiagnosticManagement/aapFunctionalCluster_DiagnosticManagement.cpp"]
   ,  deps = [
            "//repo_projects/pProjectVirtualEcu/main_LATEST:common"
         ,  "//repo_projects/pProjectVirtualEcu/main_LATEST:SwcServiceEcuM"
         ,  "//repo_projects/pProjectVirtualEcu/main_LATEST:SwcServiceEthTp"
      ]
   ,  hdrs = [
            "source/aapFunctionalCluster_DiagnosticManagement/infClientSwcServiceDcm.hpp"
         ,  "source/aapFunctionalCluster_DiagnosticManagement/interface_DiagnosticManagement_CancellationHandler.hpp"
         ,  "source/aapFunctionalCluster_DiagnosticManagement/interface_DiagnosticManagement_Condition.hpp"
         ,  "source/aapFunctionalCluster_DiagnosticManagement/interface_DiagnosticManagement_Conversation.hpp"
         ,  "source/aapFunctionalCluster_DiagnosticManagement/interface_DiagnosticManagement_DTCInformation.hpp"
         ,  "source/aapFunctionalCluster_DiagnosticManagement/interface_DiagnosticManagement_Event.hpp"
         ,  "source/aapFunctionalCluster_DiagnosticManagement/interface_DiagnosticManagement_Indicator.hpp"
         ,  "source/aapFunctionalCluster_DiagnosticManagement/interface_DiagnosticManagement_MetaInfo.hpp"
         ,  "source/aapFunctionalCluster_DiagnosticManagement/interface_DiagnosticManagement_Monitor.hpp"
         ,  "source/aapFunctionalCluster_DiagnosticManagement/interface_DiagnosticManagement_MultipleCondition.hpp"
         ,  "source/aapFunctionalCluster_DiagnosticManagement/interface_DiagnosticManagement_MultipleEvent.hpp"
         ,  "source/aapFunctionalCluster_DiagnosticManagement/interface_DiagnosticManagement_MultipleMonitor.hpp"
         ,  "source/aapFunctionalCluster_DiagnosticManagement/interface_DiagnosticManagement_OperationCycle.hpp"
      ]
   ,  includes   = ["./source/aapFunctionalCluster_DiagnosticManagement"]
   ,  visibility = ["//visibility:public"]
)

cc_library(
      name = "aapFunctionalCluster_ExecutionManagement"
   ,  srcs = ["source/aapFunctionalCluster_ExecutionManagement/aapFunctionalCluster_ExecutionManagement.cpp"]
   ,  deps = [
            "//repo_projects/pProjectVirtualEcu/main_LATEST:common"
         ,  "//repo_projects/pProjectVirtualEcu/main_LATEST:aapFunctionalCluster_DiagnosticManagement"
         ,  "//repo_projects/pProjectVirtualEcu/main_LATEST:SwcServiceEcuM"
         ,  "//repo_projects/pProjectVirtualEcu/main_LATEST:SwcServiceEthTp"
      ]
   ,  hdrs = [
            "source/aapFunctionalCluster_ExecutionManagement/interface_ExecutionManagement_ExecutionClient.hpp"
      ]
   ,  includes   = ["./source/aapFunctionalCluster_ExecutionManagement"]
   ,  visibility = ["//visibility:public"]
)

cc_library(
      name = "aapFunctionalCluster_Firewall"
   ,  srcs = ["source/aapFunctionalCluster_Firewall/aapFunctionalCluster_Firewall.cpp"]
#  ,  deps = ["//repo_projects/pProjectVirtualEcu/main_LATEST:SwcServiceEcuM"]
   ,  hdrs = [
            "source/aapFunctionalCluster_Firewall/interface_Firewall_FirewallStateSwitch.hpp"
      ]
   ,  includes   = ["./source/aapFunctionalCluster_Firewall"]
   ,  visibility = ["//visibility:public"]
)

cc_library(
      name       = "aapFunctionalCluster_IntrusionDetectionSystemManager"
   ,  srcs       = ["source/aapFunctionalCluster_IntrusionDetectionSystemManager/aapFunctionalCluster_IntrusionDetectionSystemManager.cpp"]
#  ,  deps       = ["//repo_projects/pProjectVirtualEcu/main_LATEST:SwcServiceEcuM"]
   ,  hdrs       = [
            "source/aapFunctionalCluster_IntrusionDetectionSystemManager/interface_IntrusionDetectionSystemManager_EventReporter.hpp"
      ]
   ,  includes   = ["./source/aapFunctionalCluster_IntrusionDetectionSystemManager"]
   ,  visibility = ["//visibility:public"]
)

cc_library(
      name       = "aapFunctionalCluster_LogAndTrace"
   ,  srcs       = ["source/aapFunctionalCluster_LogAndTrace/aapFunctionalCluster_LogAndTrace.cpp"]
   ,  deps       = [
            "//repo_projects/pProjectVirtualEcu/main_LATEST:common"
      ]
   ,  hdrs       = [
            "source/aapFunctionalCluster_LogAndTrace/interface_LogAndTrace.hpp"
         ,  "source/aapFunctionalCluster_LogAndTrace/interface_LogAndTrace_Logger.hpp"
         ,  "source/aapFunctionalCluster_LogAndTrace/interface_LogAndTrace_LogStream.hpp"
      ]
   ,  includes   = ["./source/aapFunctionalCluster_LogAndTrace"]
   ,  visibility = ["//visibility:public"]
)

cc_library(
      name       = "aapFunctionalCluster_NetworkManagement"
   ,  srcs       = ["source/aapFunctionalCluster_NetworkManagement/aapFunctionalCluster_NetworkManagement.cpp"]
#  ,  deps       = ["//repo_projects/pProjectVirtualEcu/main_LATEST:SwcServiceEcuM"]
   ,  hdrs       = [
            "source/aapFunctionalCluster_NetworkManagement/interface_NetworkManagement_NetworkHandle.hpp"
      ]
   ,  includes   = ["./source/aapFunctionalCluster_NetworkManagement"]
   ,  visibility = ["//visibility:public"]
)

cc_library(
      name       = "aapFunctionalCluster_Persistency"
   ,  srcs       = ["source/aapFunctionalCluster_Persistency/aapFunctionalCluster_Persistency.cpp"]
   ,  deps       = [
            "//repo_projects/pProjectVirtualEcu/main_LATEST:common"
      ]
   ,  hdrs       = [
            "source/aapFunctionalCluster_Persistency/interface_Persistency_FileStorage.hpp"
         ,  "source/aapFunctionalCluster_Persistency/interface_Persistency.hpp"
         ,  "source/aapFunctionalCluster_Persistency/interface_Persistency_KeyValueStorage.hpp"
         ,  "source/aapFunctionalCluster_Persistency/interface_Persistency_ReadAccessor.hpp"
         ,  "source/aapFunctionalCluster_Persistency/interface_Persistency_ReadWriteAccessor.hpp"
      ]
   ,  includes   = ["./source/aapFunctionalCluster_Persistency"]
   ,  visibility = ["//visibility:public"]
)

cc_library(
      name       = "aapFunctionalCluster_PlatformHealthManagement"
   ,  srcs       = ["source/aapFunctionalCluster_PlatformHealthManagement/aapFunctionalCluster_PlatformHealthManagement.cpp"]
#  ,  deps       = ["//repo_projects/pProjectVirtualEcu/main_LATEST:SwcServiceEcuM"]
   ,  hdrs       = [
            "source/aapFunctionalCluster_PlatformHealthManagement/interface_PlatformHealthManagement_RecoveryAction.hpp"
         ,  "source/aapFunctionalCluster_PlatformHealthManagement/interface_PlatformHealthManagement_SupervisedEntity.hpp"
      ]
   ,  includes   = ["./source/aapFunctionalCluster_PlatformHealthManagement"]
   ,  visibility = ["//visibility:public"]
)

cc_library(
      name       = "aapFunctionalCluster_RawDataStream"
   ,  srcs       = ["source/aapFunctionalCluster_RawDataStream/aapFunctionalCluster_RawDataStream.cpp"]
#  ,  deps       = ["//repo_projects/pProjectVirtualEcu/main_LATEST:SwcServiceEcuM"]
   ,  hdrs       = [
            "source/aapFunctionalCluster_RawDataStream/interface_RawDataStream_RawDataStreamClient.hpp"
         ,  "source/aapFunctionalCluster_RawDataStream/interface_RawDataStream_RawDataStreamServer.hpp"
      ]
   ,  includes   = ["./source/aapFunctionalCluster_RawDataStream"]
   ,  visibility = ["//visibility:public"]
)

cc_library(
      name       = "aapFunctionalCluster_Registry"
   ,  srcs       = ["source/aapFunctionalCluster_Registry/aapFunctionalCluster_Registry.cpp"]
#  ,  deps       = ["//repo_projects/pProjectVirtualEcu/main_LATEST:SwcServiceEcuM"]
   ,  hdrs       = [
            "source/aapFunctionalCluster_Registry/interface_Registry_ManifestAccessor.hpp"
      ]
   ,  includes   = ["./source/aapFunctionalCluster_Registry"]
   ,  visibility = ["//visibility:public"]
)

cc_library(
      name       = "aapFunctionalCluster_StateManagement"
   ,  srcs       = ["source/aapFunctionalCluster_StateManagement/aapFunctionalCluster_StateManagement.cpp"]
   ,  deps       = [
            "//repo_projects/pProjectVirtualEcu/main_LATEST:common"
      ]
   ,  hdrs       = [
            "source/aapFunctionalCluster_StateManagement/interface_StateManagement_EcuResetRequest.hpp"
         ,  "source/aapFunctionalCluster_StateManagement/interface_StateManagement_PowerMode.hpp"
         ,  "source/aapFunctionalCluster_StateManagement/interface_StateManagement_RecoveryAction.hpp"
         ,  "source/aapFunctionalCluster_StateManagement/interface_StateManagement_StateClient.hpp"
         ,  "source/aapFunctionalCluster_StateManagement/interface_StateManagement_StateMachineService.hpp"
         ,  "source/aapFunctionalCluster_StateManagement/interface_StateManagement_UpdateAllowedService.hpp"
         ,  "source/aapFunctionalCluster_StateManagement/interface_StateManagement_UpdateRequest.hpp"
      ]
   ,  includes   = ["./source/aapFunctionalCluster_StateManagement"]
   ,  visibility = ["//visibility:public"]
)

cc_library(
      name       = "aapFunctionalCluster_TimeSynchronization"
   ,  srcs       = ["source/aapFunctionalCluster_TimeSynchronization/aapFunctionalCluster_TimeSynchronization.cpp"]
   ,  deps       = [
            "//repo_projects/pProjectVirtualEcu/main_LATEST:common"
      ]
   ,  hdrs       = [
            "source/aapFunctionalCluster_TimeSynchronization/interface_TimeSynchronization_OffsetTimeBaseProvider.hpp"
         ,  "source/aapFunctionalCluster_TimeSynchronization/interface_TimeSynchronization_SynchronizedTimeBaseConsumer.hpp"
         ,  "source/aapFunctionalCluster_TimeSynchronization/interface_TimeSynchronization_SynchronizedTimeBaseProvider.hpp"
         ,  "source/aapFunctionalCluster_TimeSynchronization/interface_TimeSynchronization_SynchronizedTimeBaseStatus.hpp"
      ]
   ,  includes   = ["./source/aapFunctionalCluster_TimeSynchronization"]
   ,  visibility = ["//visibility:public"]
)

cc_library(
      name       = "aapFunctionalCluster_UpdateAndConfigurationManagement"
   ,  srcs       = ["source/aapFunctionalCluster_UpdateAndConfigurationManagement/aapFunctionalCluster_UpdateAndConfigurationManagement.cpp"]
   ,  deps       = [
            "//repo_projects/pProjectVirtualEcu/main_LATEST:common"
      ]
   ,  hdrs       = [
            "source/aapFunctionalCluster_UpdateAndConfigurationManagement/interface_UpdateAndConfigurationManagement_PackageManagement.hpp"
      ]
   ,  includes   = ["./source/aapFunctionalCluster_UpdateAndConfigurationManagement"]
   ,  visibility = ["//visibility:public"]
)

cc_library(
      name       = "aapFunctionalCluster_VehicleUpdateAndConfigurationManagement"
   ,  srcs       = ["source/aapFunctionalCluster_VehicleUpdateAndConfigurationManagement/aapFunctionalCluster_VehicleUpdateAndConfigurationManagement.cpp"]
   ,  deps       = [
            "//repo_projects/pProjectVirtualEcu/main_LATEST:common"
      ]
   ,  hdrs       = [
            "source/aapFunctionalCluster_VehicleUpdateAndConfigurationManagement/interface_VehicleUpdateAndConfigurationManagement_VehicleDriverApplication.hpp"
         ,  "source/aapFunctionalCluster_VehicleUpdateAndConfigurationManagement/interface_VehicleUpdateAndConfigurationManagement_VehiclePackageManagement.hpp"
         ,  "source/aapFunctionalCluster_VehicleUpdateAndConfigurationManagement/interface_VehicleUpdateAndConfigurationManagement_VehicleStateManager.hpp"
      ]
   ,  includes   = ["./source/aapFunctionalCluster_VehicleUpdateAndConfigurationManagement"]
   ,  visibility = ["//visibility:public"]
)

cc_library(
      name = "SwcServiceEcuM"
   ,  srcs = ["source/SwcServiceEcuM/SwcServiceEcuM.cpp"]
   ,  deps = [
            "//repo_projects/pProjectVirtualEcu/main_LATEST:common"
      ]
   ,  hdrs = [
            "source/SwcServiceEcuM/infClientSwcServiceEcuM.hpp"
      ]
   ,  includes   = ["./source/SwcServiceEcuM"]
   ,  visibility = ["//visibility:public"]
)

cc_library(
      name = "SwcServiceEthTp"
   ,  srcs = [
            "source/SwcServiceEthTp/SwcServiceEthTp.cpp"
         ,  "source/SwcServiceEthTp/CfgMcalEth.cpp"
      ]
   ,  deps = [
            "//repo_projects/pProjectVirtualEcu/main_LATEST:common"
      ]
   ,  hdrs = [
            "source/SwcServiceEthTp/infClientSwcServiceEthTp.hpp"
         ,  "source/SwcServiceEthTp/infClientCfgMcalEth.hpp"
      ]
   ,  includes   = ["./source/SwcServiceEthTp"]
   ,  visibility = ["//visibility:public"]
)

cc_binary(
      name = "pProjectVirtualEcu_main_LATEST"
   ,  deps = [
            "//repo_projects/pProjectVirtualEcu/main_LATEST:common"
         ,  "//repo_projects/pProjectVirtualEcu/main_LATEST:aapFunctionalCluster_CommunicationManagement"
         ,  "//repo_projects/pProjectVirtualEcu/main_LATEST:aapFunctionalCluster_Core"
         ,  "//repo_projects/pProjectVirtualEcu/main_LATEST:aapFunctionalCluster_Cryptography"
         ,  "//repo_projects/pProjectVirtualEcu/main_LATEST:aapFunctionalCluster_DiagnosticManagement"
         ,  "//repo_projects/pProjectVirtualEcu/main_LATEST:aapFunctionalCluster_ExecutionManagement"
         ,  "//repo_projects/pProjectVirtualEcu/main_LATEST:aapFunctionalCluster_Firewall"
         ,  "//repo_projects/pProjectVirtualEcu/main_LATEST:aapFunctionalCluster_IntrusionDetectionSystemManager"
         ,  "//repo_projects/pProjectVirtualEcu/main_LATEST:aapFunctionalCluster_LogAndTrace"
         ,  "//repo_projects/pProjectVirtualEcu/main_LATEST:aapFunctionalCluster_NetworkManagement"
         ,  "//repo_projects/pProjectVirtualEcu/main_LATEST:aapFunctionalCluster_Persistency"
         ,  "//repo_projects/pProjectVirtualEcu/main_LATEST:aapFunctionalCluster_PlatformHealthManagement"
         ,  "//repo_projects/pProjectVirtualEcu/main_LATEST:aapFunctionalCluster_RawDataStream"
         ,  "//repo_projects/pProjectVirtualEcu/main_LATEST:aapFunctionalCluster_Registry"
         ,  "//repo_projects/pProjectVirtualEcu/main_LATEST:aapFunctionalCluster_StateManagement"
         ,  "//repo_projects/pProjectVirtualEcu/main_LATEST:aapFunctionalCluster_TimeSynchronization"
         ,  "//repo_projects/pProjectVirtualEcu/main_LATEST:aapFunctionalCluster_UpdateAndConfigurationManagement"
         ,  "//repo_projects/pProjectVirtualEcu/main_LATEST:aapFunctionalCluster_VehicleUpdateAndConfigurationManagement"
         ,  "//repo_projects/pProjectVirtualEcu/main_LATEST:SwcServiceEcuM"
         ,  "//repo_projects/pProjectVirtualEcu/main_LATEST:SwcServiceEthTp"
      ]
   ,  visibility = ["//visibility:public"]
)

