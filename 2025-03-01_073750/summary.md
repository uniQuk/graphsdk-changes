# Microsoft Graph API Change Report

## Comprehensive Summary for All Versions
Generated on 2025-03-01 07:37:50

### Overall Statistics
- **Total Cmdlets**: 24265
- **Total Endpoints**: 21138
- **Total Scopes**: 351
- **Total Cmdlet Changes**: 3943
- **Total Endpoint Changes**: 19
- **Total Scope Changes**: 0

### Detailed Statistics by Version

#### v1.0
- Cmdlet Changes: Added: 408, Removed: 0, Modified: 1002
- Endpoint Changes: Added: 0, Removed: 0, Modified: 18

#### beta
- Cmdlet Changes: Added: 737, Removed: 0, Modified: 1796
- Endpoint Changes: Added: 0, Removed: 0, Modified: 1

#### scopes
- Scope Changes: Added: 0, Removed: 0, Modified: 0


---

### Detailed Cmdlet Changes

# Cmdlet v1.0 Changes

## Statistics
- **Total cmdlets**: 9144
- **Total cmdlet changes**: 1410
- **Added**: 408
- **Removed**: 0
- **Modified**: 1002

### Added Cmdlets (408)

| Command |
|---------|
| Add-MgGroupTeamChannelMember |
| Add-MgGroupTeamMember |
| Add-MgGroupTeamPrimaryChannelMember |
| Clear-MgGroupTeamChannelMessageReaction |
| Clear-MgGroupTeamChannelMessageReplyReaction |
| Clear-MgGroupTeamPrimaryChannelMessageReaction |
| Clear-MgGroupTeamPrimaryChannelMessageReplyReaction |
| Complete-MgGroupTeamChannelMigration |
| Complete-MgGroupTeamMigration |
| Complete-MgGroupTeamPrimaryChannelMigration |
| Copy-MgGroupOnenoteNotebookSectionGroupSectionPageToSection |
| Copy-MgGroupOnenoteNotebookSectionGroupSectionToNotebook |
| Copy-MgGroupOnenoteNotebookSectionGroupSectionToSectionGroup |
| Copy-MgGroupOnenoteNotebookSectionPageToSection |
| Copy-MgGroupOnenoteNotebookSectionToNotebook |
| Copy-MgGroupOnenoteNotebookSectionToSectionGroup |
| Copy-MgGroupOnenoteSectionGroupSectionPageToSection |
| Copy-MgGroupOnenoteSectionGroupSectionToNotebook |
| Copy-MgGroupOnenoteSectionGroupSectionToSectionGroup |
| Copy-MgGroupOnenoteSectionPageToSection |
| Copy-MgGroupSiteOnenoteNotebook |
| Copy-MgGroupSiteOnenoteNotebookSectionGroupSectionPageToSection |
| Copy-MgGroupSiteOnenoteNotebookSectionGroupSectionToNotebook |
| Copy-MgGroupSiteOnenoteNotebookSectionGroupSectionToSectionGroup |
| Copy-MgGroupSiteOnenoteNotebookSectionPageToSection |
| Copy-MgGroupSiteOnenoteNotebookSectionToNotebook |
| Copy-MgGroupSiteOnenoteNotebookSectionToSectionGroup |
| Copy-MgGroupSiteOnenotePageToSection |
| Copy-MgGroupSiteOnenoteSectionGroupSectionPageToSection |
| Copy-MgGroupSiteOnenoteSectionGroupSectionToNotebook |
| Copy-MgGroupSiteOnenoteSectionGroupSectionToSectionGroup |
| Copy-MgGroupSiteOnenoteSectionPageToSection |
| Copy-MgGroupSiteOnenoteSectionToNotebook |
| Copy-MgGroupSiteOnenoteSectionToSectionGroup |
| Copy-MgGroupTeam |
| Copy-MgUserOnenoteNotebookSectionGroupSectionPageToSection |
| Copy-MgUserOnenoteNotebookSectionGroupSectionToNotebook |
| Copy-MgUserOnenoteNotebookSectionGroupSectionToSectionGroup |
| Copy-MgUserOnenoteNotebookSectionPageToSection |
| Copy-MgUserOnenoteNotebookSectionToNotebook |
| Copy-MgUserOnenoteNotebookSectionToSectionGroup |
| Copy-MgUserOnenoteSectionGroupSectionPageToSection |
| Copy-MgUserOnenoteSectionGroupSectionToNotebook |
| Copy-MgUserOnenoteSectionGroupSectionToSectionGroup |
| Copy-MgUserOnenoteSectionPageToSection |
| Disable-MgMeAuthenticationPhoneMethodSmsSignIn |
| Enable-MgMeAuthenticationPhoneMethodSmsSignIn |
| Enable-MgSolutionBackupRestore |
| Export-MgSecurityCaseEdiscoveryCaseSearchReport |
| Export-MgSecurityCaseEdiscoveryCaseSearchResult |
| Find-MgTenantRelationshipTenantInformationByDomainName |
| Find-MgTenantRelationshipTenantInformationByTenantId |
| Get-MgDeviceManagementManagedDeviceCategoryByRef |
| Get-MgDeviceManagementReportDeviceAppInstallationStatusReport |
| Get-MgDeviceManagementVirtualEndpointProvisioningPolicyAssignmentAssignedUserByUserPrincipalName |
| Get-MgGroupEventInstanceDelta |
| Get-MgGroupOnenote |
| Get-MgGroupOnenoteNotebookRecentNotebook |
| Get-MgGroupOnenoteNotebookSectionCount |
| Get-MgGroupOnenoteNotebookSectionGroupCount |
| Get-MgGroupOnenoteNotebookSectionGroupParentNotebook |
| Get-MgGroupOnenoteNotebookSectionGroupParentSectionGroup |
| Get-MgGroupOnenoteNotebookSectionGroupSection |
| Get-MgGroupOnenoteNotebookSectionGroupSectionCount |
| Get-MgGroupOnenoteNotebookSectionGroupSectionPage |
| Get-MgGroupOnenoteNotebookSectionGroupSectionPageContent |
| Get-MgGroupOnenoteNotebookSectionGroupSectionPageCount |
| Get-MgGroupOnenoteNotebookSectionGroupSectionPageParentNotebook |
| Get-MgGroupOnenoteNotebookSectionGroupSectionPageParentSection |
| Get-MgGroupOnenoteNotebookSectionGroupSectionParentNotebook |
| Get-MgGroupOnenoteNotebookSectionGroupSectionParentSectionGroup |
| Get-MgGroupOnenoteNotebookSectionPage |
| Get-MgGroupOnenoteNotebookSectionPageContent |
| Get-MgGroupOnenoteNotebookSectionPageCount |
| Get-MgGroupOnenoteNotebookSectionPageParentNotebook |
| Get-MgGroupOnenoteNotebookSectionPageParentSection |
| Get-MgGroupOnenoteNotebookSectionParentNotebook |
| Get-MgGroupOnenoteNotebookSectionParentSectionGroup |
| Get-MgGroupOnenotePageParentNotebook |
| Get-MgGroupOnenotePageParentSection |
| Get-MgGroupOnenoteSectionGroupParentNotebook |
| Get-MgGroupOnenoteSectionGroupParentSectionGroup |
| Get-MgGroupOnenoteSectionGroupSectionCount |
| Get-MgGroupOnenoteSectionGroupSectionPage |
| Get-MgGroupOnenoteSectionGroupSectionPageContent |
| Get-MgGroupOnenoteSectionGroupSectionPageCount |
| Get-MgGroupOnenoteSectionGroupSectionPageParentNotebook |
| Get-MgGroupOnenoteSectionGroupSectionPageParentSection |
| Get-MgGroupOnenoteSectionGroupSectionParentNotebook |
| Get-MgGroupOnenoteSectionGroupSectionParentSectionGroup |
| Get-MgGroupOnenoteSectionPageContent |
| Get-MgGroupOnenoteSectionPageCount |
| Get-MgGroupOnenoteSectionPageParentNotebook |
| Get-MgGroupOnenoteSectionPageParentSection |
| Get-MgGroupOnenoteSectionParentNotebook |
| Get-MgGroupOnenoteSectionParentSectionGroup |
| Get-MgGroupSiteOnenoteNotebookFromWebUrl |
| Get-MgGroupSiteOnenoteNotebookRecentNotebook |
| Get-MgGroupTeamChannelMessageDelta |
| Get-MgGroupTeamChannelMessageReplyDelta |
| Get-MgGroupTeamChannelRetainedMessage |
| Get-MgGroupTeamPrimaryChannelMessageDelta |
| Get-MgGroupTeamPrimaryChannelMessageReplyDelta |
| Get-MgMeAuthentication |
| Get-MgMeAuthenticationEmailMethod |
| Get-MgMeAuthenticationEmailMethodCount |
| Get-MgMeAuthenticationFido2Method |
| Get-MgMeAuthenticationFido2MethodCount |
| Get-MgMeAuthenticationMethod |
| Get-MgMeAuthenticationMethodCount |
| Get-MgMeAuthenticationMicrosoftAuthenticatorMethod |
| Get-MgMeAuthenticationMicrosoftAuthenticatorMethodCount |
| Get-MgMeAuthenticationMicrosoftAuthenticatorMethodDevice |
| Get-MgMeAuthenticationOperation |
| Get-MgMeAuthenticationOperationCount |
| Get-MgMeAuthenticationPasswordMethod |
| Get-MgMeAuthenticationPasswordMethodCount |
| Get-MgMeAuthenticationPhoneMethod |
| Get-MgMeAuthenticationPhoneMethodCount |
| Get-MgMeAuthenticationSoftwareOathMethod |
| Get-MgMeAuthenticationSoftwareOathMethodCount |
| Get-MgMeAuthenticationTemporaryAccessPassMethod |
| Get-MgMeAuthenticationTemporaryAccessPassMethodCount |
| Get-MgMeAuthenticationWindowsHelloForBusinessMethod |
| Get-MgMeAuthenticationWindowsHelloForBusinessMethodCount |
| Get-MgMeAuthenticationWindowsHelloForBusinessMethodDevice |
| Get-MgPrivacySubjectRightsRequestApproverByUserPrincipalName |
| Get-MgPrivacySubjectRightsRequestCollaboratorByUserPrincipalName |
| Get-MgPrivacySubjectRightsRequestFinalAttachment |
| Get-MgPrivacySubjectRightsRequestFinalReport |
| Get-MgSecurityIdentitySensor |
| Get-MgSecurityIdentitySensorCount |
| Get-MgSecurityIdentitySensorDeploymentAccessKey |
| Get-MgSecurityIdentitySensorDeploymentPackageUri |
| Get-MgSecurityIdentitySensorHealthIssue |
| Get-MgSecurityIdentitySensorHealthIssueCount |
| Get-MgSecuritySubjectRightsRequestApproverByUserPrincipalName |
| Get-MgSecuritySubjectRightsRequestCollaboratorByUserPrincipalName |
| Get-MgSiteOnenote |
| Get-MgSiteOnenoteNotebookRecentNotebook |
| Get-MgSiteOnenoteNotebookSectionCount |
| Get-MgSiteOnenoteNotebookSectionGroupCount |
| Get-MgSiteOnenoteNotebookSectionGroupParentNotebook |
| Get-MgSiteOnenoteNotebookSectionGroupParentSectionGroup |
| Get-MgSiteOnenoteNotebookSectionGroupSection |
| Get-MgSiteOnenoteNotebookSectionGroupSectionCount |
| Get-MgSiteOnenoteNotebookSectionGroupSectionPage |
| Get-MgSiteOnenoteNotebookSectionGroupSectionPageContent |
| Get-MgSiteOnenoteNotebookSectionGroupSectionPageCount |
| Get-MgSiteOnenoteNotebookSectionGroupSectionPageParentNotebook |
| Get-MgSiteOnenoteNotebookSectionGroupSectionPageParentSection |
| Get-MgSiteOnenoteNotebookSectionGroupSectionParentNotebook |
| Get-MgSiteOnenoteNotebookSectionGroupSectionParentSectionGroup |
| Get-MgSiteOnenoteNotebookSectionPage |
| Get-MgSiteOnenoteNotebookSectionPageContent |
| Get-MgSiteOnenoteNotebookSectionPageCount |
| Get-MgSiteOnenoteNotebookSectionPageParentNotebook |
| Get-MgSiteOnenoteNotebookSectionPageParentSection |
| Get-MgSiteOnenoteNotebookSectionParentNotebook |
| Get-MgSiteOnenoteNotebookSectionParentSectionGroup |
| Get-MgSiteOnenotePageParentNotebook |
| Get-MgSiteOnenotePageParentSection |
| Get-MgSiteOnenoteSectionGroupParentNotebook |
| Get-MgSiteOnenoteSectionGroupParentSectionGroup |
| Get-MgSiteOnenoteSectionGroupSectionCount |
| Get-MgSiteOnenoteSectionGroupSectionPage |
| Get-MgSiteOnenoteSectionGroupSectionPageContent |
| Get-MgSiteOnenoteSectionGroupSectionPageCount |
| Get-MgSiteOnenoteSectionGroupSectionPageParentNotebook |
| Get-MgSiteOnenoteSectionGroupSectionPageParentSection |
| Get-MgSiteOnenoteSectionGroupSectionParentNotebook |
| Get-MgSiteOnenoteSectionGroupSectionParentSectionGroup |
| Get-MgSiteOnenoteSectionPageContent |
| Get-MgSiteOnenoteSectionPageCount |
| Get-MgSiteOnenoteSectionPageParentNotebook |
| Get-MgSiteOnenoteSectionPageParentSection |
| Get-MgSiteOnenoteSectionParentNotebook |
| Get-MgSiteOnenoteSectionParentSectionGroup |
| Get-MgUserByUserPrincipalName |
| Get-MgUserManagedDeviceCategoryByRef |
| Get-MgUserOnenote |
| Get-MgUserOnenoteNotebookRecentNotebook |
| Get-MgUserOnenoteNotebookSectionCount |
| Get-MgUserOnenoteNotebookSectionGroupCount |
| Get-MgUserOnenoteNotebookSectionGroupParentNotebook |
| Get-MgUserOnenoteNotebookSectionGroupParentSectionGroup |
| Get-MgUserOnenoteNotebookSectionGroupSection |
| Get-MgUserOnenoteNotebookSectionGroupSectionCount |
| Get-MgUserOnenoteNotebookSectionGroupSectionPage |
| Get-MgUserOnenoteNotebookSectionGroupSectionPageContent |
| Get-MgUserOnenoteNotebookSectionGroupSectionPageCount |
| Get-MgUserOnenoteNotebookSectionGroupSectionPageParentNotebook |
| Get-MgUserOnenoteNotebookSectionGroupSectionPageParentSection |
| Get-MgUserOnenoteNotebookSectionGroupSectionParentNotebook |
| Get-MgUserOnenoteNotebookSectionGroupSectionParentSectionGroup |
| Get-MgUserOnenoteNotebookSectionPage |
| Get-MgUserOnenoteNotebookSectionPageContent |
| Get-MgUserOnenoteNotebookSectionPageCount |
| Get-MgUserOnenoteNotebookSectionPageParentNotebook |
| Get-MgUserOnenoteNotebookSectionPageParentSection |
| Get-MgUserOnenoteNotebookSectionParentNotebook |
| Get-MgUserOnenoteNotebookSectionParentSectionGroup |
| Get-MgUserOnenotePageParentNotebook |
| Get-MgUserOnenotePageParentSection |
| Get-MgUserOnenoteSectionGroupParentNotebook |
| Get-MgUserOnenoteSectionGroupParentSectionGroup |
| Get-MgUserOnenoteSectionGroupSectionCount |
| Get-MgUserOnenoteSectionGroupSectionPage |
| Get-MgUserOnenoteSectionGroupSectionPageContent |
| Get-MgUserOnenoteSectionGroupSectionPageCount |
| Get-MgUserOnenoteSectionGroupSectionPageParentNotebook |
| Get-MgUserOnenoteSectionGroupSectionPageParentSection |
| Get-MgUserOnenoteSectionGroupSectionParentNotebook |
| Get-MgUserOnenoteSectionGroupSectionParentSectionGroup |
| Get-MgUserOnenoteSectionPageContent |
| Get-MgUserOnenoteSectionPageCount |
| Get-MgUserOnenoteSectionPageParentNotebook |
| Get-MgUserOnenoteSectionPageParentSection |
| Get-MgUserOnenoteSectionParentNotebook |
| Get-MgUserOnenoteSectionParentSectionGroup |
| Get-MgVirtualEventTownhallByUserIdAndRole |
| Get-MgVirtualEventTownhallByUserRole |
| Initialize-MgSolutionBackupRestoreProtectionPolicy |
| Initialize-MgSolutionBackupRestoreServiceApp |
| Initialize-MgSolutionBackupRestoreSession |
| Invoke-MgAcceptGroupEventInstance |
| Invoke-MgAcceptGroupEventInstanceTentatively |
| Invoke-MgArchiveGroupTeam |
| Invoke-MgArchiveGroupTeamChannel |
| Invoke-MgArchiveGroupTeamPrimaryChannel |
| Invoke-MgCalendarUserCalendar |
| Invoke-MgDeclineGroupEventInstance |
| Invoke-MgDismissGroupEventInstanceReminder |
| Invoke-MgForwardGroupEventInstance |
| Invoke-MgHaveGroupTeamChannel |
| Invoke-MgHaveGroupTeamPrimaryChannel |
| Invoke-MgPreviewGroupOnenoteNotebookSectionGroupSectionPage |
| Invoke-MgPreviewGroupOnenoteNotebookSectionPage |
| Invoke-MgPreviewGroupOnenoteSectionGroupSectionPage |
| Invoke-MgPreviewGroupOnenoteSectionPage |
| Invoke-MgPreviewGroupSiteOnenoteNotebookSectionGroupSectionPage |
| Invoke-MgPreviewGroupSiteOnenoteNotebookSectionPage |
| Invoke-MgPreviewGroupSiteOnenotePage |
| Invoke-MgPreviewGroupSiteOnenoteSectionGroupSectionPage |
| Invoke-MgPreviewGroupSiteOnenoteSectionPage |
| Invoke-MgPreviewUserOnenoteNotebookSectionGroupSectionPage |
| Invoke-MgPreviewUserOnenoteNotebookSectionPage |
| Invoke-MgPreviewUserOnenoteSectionGroupSectionPage |
| Invoke-MgPreviewUserOnenoteSectionPage |
| Invoke-MgShareGroupTeamSchedule |
| Invoke-MgSnoozeGroupEventInstanceReminder |
| Invoke-MgSoftGroupTeamChannelMessageDelete |
| Invoke-MgSoftGroupTeamChannelMessageReplyDelete |
| Invoke-MgSoftGroupTeamPrimaryChannelMessageDelete |
| Invoke-MgSoftGroupTeamPrimaryChannelMessageReplyDelete |
| Invoke-MgUnarchiveGroupTeam |
| Invoke-MgUnarchiveGroupTeamChannel |
| Invoke-MgUnarchiveGroupTeamPrimaryChannel |
| New-MgGroupEventAttachmentUploadSession |
| New-MgGroupEventInstanceAttachmentUploadSession |
| New-MgGroupMember |
| New-MgGroupOnenoteNotebookSectionGroupSection |
| New-MgGroupOnenoteNotebookSectionGroupSectionPage |
| New-MgGroupOnenoteNotebookSectionPage |
| New-MgGroupOnenoteOperation |
| New-MgGroupOnenoteResource |
| New-MgGroupOnenoteSectionGroupSectionPage |
| New-MgGroupTeamChannelEmail |
| New-MgGroupTeamPrimaryChannelEmail |
| New-MgMeAuthenticationEmailMethod |
| New-MgMeAuthenticationMethod |
| New-MgMeAuthenticationOperation |
| New-MgMeAuthenticationPasswordMethod |
| New-MgMeAuthenticationPhoneMethod |
| New-MgMeAuthenticationTemporaryAccessPassMethod |
| New-MgSecurityIdentitySensor |
| New-MgSecurityIdentitySensorDeploymentAccessKey |
| New-MgSiteOnenoteNotebookSectionGroupSection |
| New-MgSiteOnenoteNotebookSectionGroupSectionPage |
| New-MgSiteOnenoteNotebookSectionPage |
| New-MgSiteOnenoteOperation |
| New-MgSiteOnenoteResource |
| New-MgSiteOnenoteSectionGroupSectionPage |
| New-MgUserManagedDeviceLogCollectionRequestDownloadUrl |
| New-MgUserOnenoteNotebookSectionGroupSection |
| New-MgUserOnenoteNotebookSectionGroupSectionPage |
| New-MgUserOnenoteNotebookSectionPage |
| New-MgUserOnenoteOperation |
| New-MgUserOnenoteResource |
| New-MgUserOnenoteSectionGroupSectionPage |
| Publish-MgAdminEdgeInternetExplorerModeSiteList |
| Remove-MgDeviceManagementManagedDeviceCategoryByRef |
| Remove-MgDriveItemCheckout |
| Remove-MgDriveRootCheckout |
| Remove-MgGroupDriveItemCheckout |
| Remove-MgGroupDriveRootCheckout |
| Remove-MgGroupOnenote |
| Remove-MgGroupOnenoteNotebookSection |
| Remove-MgGroupOnenoteNotebookSectionGroup |
| Remove-MgGroupOnenoteNotebookSectionGroupSection |
| Remove-MgGroupOnenoteNotebookSectionGroupSectionPage |
| Remove-MgGroupOnenoteNotebookSectionGroupSectionPageContent |
| Remove-MgGroupOnenoteNotebookSectionPage |
| Remove-MgGroupOnenoteNotebookSectionPageContent |
| Remove-MgGroupOnenoteOperation |
| Remove-MgGroupOnenoteResource |
| Remove-MgGroupOnenoteResourceContent |
| Remove-MgGroupOnenoteSectionGroupSection |
| Remove-MgGroupOnenoteSectionGroupSectionPage |
| Remove-MgGroupOnenoteSectionGroupSectionPageContent |
| Remove-MgGroupOnenoteSectionPage |
| Remove-MgGroupOnenoteSectionPageContent |
| Remove-MgGroupTeamChannelEmail |
| Remove-MgGroupTeamPrimaryChannelEmail |
| Remove-MgMeAuthentication |
| Remove-MgMeAuthenticationEmailMethod |
| Remove-MgMeAuthenticationFido2Method |
| Remove-MgMeAuthenticationMicrosoftAuthenticatorMethod |
| Remove-MgMeAuthenticationOperation |
| Remove-MgMeAuthenticationPhoneMethod |
| Remove-MgMeAuthenticationSoftwareOathMethod |
| Remove-MgMeAuthenticationTemporaryAccessPassMethod |
| Remove-MgMeAuthenticationWindowsHelloForBusinessMethod |
| Remove-MgSecurityIdentitySensor |
| Remove-MgSiteOnenote |
| Remove-MgSiteOnenoteNotebookSection |
| Remove-MgSiteOnenoteNotebookSectionGroup |
| Remove-MgSiteOnenoteNotebookSectionGroupSection |
| Remove-MgSiteOnenoteNotebookSectionGroupSectionPage |
| Remove-MgSiteOnenoteNotebookSectionPage |
| Remove-MgSiteOnenoteOperation |
| Remove-MgSiteOnenoteResource |
| Remove-MgSiteOnenoteSectionGroupSection |
| Remove-MgSiteOnenoteSectionGroupSectionPage |
| Remove-MgSiteOnenoteSectionPage |
| Remove-MgUserByUserPrincipalName |
| Remove-MgUserDriveItemCheckout |
| Remove-MgUserDriveRootCheckout |
| Remove-MgUserManagedDeviceCategoryByRef |
| Remove-MgUserOnenote |
| Remove-MgUserOnenoteNotebookSection |
| Remove-MgUserOnenoteNotebookSectionGroup |
| Remove-MgUserOnenoteNotebookSectionGroupSection |
| Remove-MgUserOnenoteNotebookSectionGroupSectionPage |
| Remove-MgUserOnenoteNotebookSectionGroupSectionPageContent |
| Remove-MgUserOnenoteNotebookSectionPage |
| Remove-MgUserOnenoteNotebookSectionPageContent |
| Remove-MgUserOnenoteOperation |
| Remove-MgUserOnenoteResource |
| Remove-MgUserOnenoteResourceContent |
| Remove-MgUserOnenoteSectionGroupSection |
| Remove-MgUserOnenoteSectionGroupSectionPage |
| Remove-MgUserOnenoteSectionGroupSectionPageContent |
| Remove-MgUserOnenoteSectionPage |
| Remove-MgUserOnenoteSectionPageContent |
| Reset-MgMeAuthenticationMethodPassword |
| Search-MgSolutionBackupRestorePoint |
| Send-MgGroupTeamActivityNotification |
| Set-MgDeviceManagementManagedDeviceCategoryByRef |
| Set-MgGroupOnenoteNotebookSectionGroupSectionPageContent |
| Set-MgGroupOnenoteNotebookSectionPageContent |
| Set-MgGroupOnenoteSectionGroupSectionPageContent |
| Set-MgGroupTeamChannelMessageReaction |
| Set-MgGroupTeamChannelMessageReplyReaction |
| Set-MgGroupTeamPrimaryChannelMessageReaction |
| Set-MgGroupTeamPrimaryChannelMessageReplyReaction |
| Set-MgSiteOnenoteNotebookSectionGroupSectionPageContent |
| Set-MgSiteOnenoteNotebookSectionPageContent |
| Set-MgSiteOnenoteSectionGroupSectionPageContent |
| Set-MgUserManagedDeviceCategoryByRef |
| Set-MgUserOnenoteNotebookSectionGroupSectionPageContent |
| Set-MgUserOnenoteNotebookSectionPageContent |
| Set-MgUserOnenoteSectionGroupSectionPageContent |
| Set-MgVirtualEventExternalEventInformation |
| Stop-MgGroupEventInstance |
| Undo-MgGroupTeamChannelMessageReplySoftDelete |
| Undo-MgGroupTeamChannelMessageSoftDelete |
| Undo-MgGroupTeamPrimaryChannelMessageReplySoftDelete |
| Undo-MgGroupTeamPrimaryChannelMessageSoftDelete |
| Update-MgGroupOnenote |
| Update-MgGroupOnenoteNotebookSection |
| Update-MgGroupOnenoteNotebookSectionGroup |
| Update-MgGroupOnenoteNotebookSectionGroupSection |
| Update-MgGroupOnenoteOperation |
| Update-MgGroupOnenoteResource |
| Update-MgGroupOnenoteSectionGroupSection |
| Update-MgGroupTeamInstalledApp |
| Update-MgMeAuthentication |
| Update-MgMeAuthenticationEmailMethod |
| Update-MgMeAuthenticationMethod |
| Update-MgMeAuthenticationOperation |
| Update-MgMeAuthenticationPhoneMethod |
| Update-MgSecurityIdentitySensor |
| Update-MgSiteOnenote |
| Update-MgSiteOnenoteNotebookSection |
| Update-MgSiteOnenoteNotebookSectionGroup |
| Update-MgSiteOnenoteNotebookSectionGroupSection |
| Update-MgSiteOnenoteOperation |
| Update-MgSiteOnenoteResource |
| Update-MgSiteOnenoteSectionGroupSection |
| Update-MgUserByUserPrincipalName |
| Update-MgUserOnenote |
| Update-MgUserOnenoteNotebookSection |
| Update-MgUserOnenoteNotebookSectionGroup |
| Update-MgUserOnenoteNotebookSectionGroupSection |
| Update-MgUserOnenoteOperation |
| Update-MgUserOnenoteResource |
| Update-MgUserOnenoteSectionGroupSection |

### Removed Cmdlets (0)

No cmdlets removed.

### Modified Cmdlets (1002)

| Command | Changes |
|---------|---------|
| Add-MgGroupDriveListContentTypeCopy | Minor changes |
| Add-MgGroupDriveListContentTypeCopyFromContentTypeHub | Minor changes |
| Add-MgGroupSite | Minor changes |
| Add-MgGroupSiteContentTypeCopy | Minor changes |
| Add-MgGroupSiteContentTypeCopyFromContentTypeHub | Minor changes |
| Add-MgGroupSiteListContentTypeCopy | Minor changes |
| Add-MgGroupSiteListContentTypeCopyFromContentTypeHub | Minor changes |
| Add-MgUserChatMember | Minor changes |
| Add-MgUserDriveListContentTypeCopy | Minor changes |
| Add-MgUserDriveListContentTypeCopyFromContentTypeHub | Minor changes |
| Add-MgUserFollowedSite | Minor changes |
| Clear-MgDeviceManagementManagedDevice | Minor changes |
| Clear-MgUserChatMessageReaction | Minor changes |
| Clear-MgUserChatMessageReplyReaction | Minor changes |
| Clear-MgUserManagedDevice | Minor changes |
| Clear-MgUserPresence | Minor changes |
| Clear-MgUserPresenceUserPreferredPresence | Minor changes |
| Copy-MgGroupDriveItem | Minor changes |
| Copy-MgGroupDriveListContentTypeToDefaultContentLocation | Minor changes |
| Copy-MgGroupDriveRoot | Minor changes |
| Copy-MgGroupOnenoteNotebook | Minor changes |
| Copy-MgGroupOnenotePageToSection | Minor changes |
| Copy-MgGroupOnenoteSectionToNotebook | Minor changes |
| Copy-MgGroupOnenoteSectionToSectionGroup | Minor changes |
| Copy-MgGroupSiteContentTypeToDefaultContentLocation | Minor changes |
| Copy-MgGroupSiteListContentTypeToDefaultContentLocation | Minor changes |
| Copy-MgSiteOnenoteNotebook | Minor changes |
| Copy-MgSiteOnenoteNotebookSectionGroupSectionPageToSection | Minor changes |
| Copy-MgSiteOnenoteNotebookSectionGroupSectionToNotebook | Minor changes |
| Copy-MgSiteOnenoteNotebookSectionGroupSectionToSectionGroup | Minor changes |
| Copy-MgSiteOnenoteNotebookSectionPageToSection | Minor changes |
| Copy-MgSiteOnenoteNotebookSectionToNotebook | Minor changes |
| Copy-MgSiteOnenoteNotebookSectionToSectionGroup | Minor changes |
| Copy-MgSiteOnenotePageToSection | Minor changes |
| Copy-MgSiteOnenoteSectionGroupSectionPageToSection | Minor changes |
| Copy-MgSiteOnenoteSectionGroupSectionToNotebook | Minor changes |
| Copy-MgSiteOnenoteSectionGroupSectionToSectionGroup | Minor changes |
| Copy-MgSiteOnenoteSectionPageToSection | Minor changes |
| Copy-MgSiteOnenoteSectionToNotebook | Minor changes |
| Copy-MgSiteOnenoteSectionToSectionGroup | Minor changes |
| Copy-MgUserDriveItem | Minor changes |
| Copy-MgUserDriveListContentTypeToDefaultContentLocation | Minor changes |
| Copy-MgUserDriveRoot | Minor changes |
| Copy-MgUserMailFolder | Minor changes |
| Copy-MgUserMailFolderChildFolder | Minor changes |
| Copy-MgUserMailFolderChildFolderMessage | Minor changes |
| Copy-MgUserMailFolderMessage | Minor changes |
| Copy-MgUserMessage | Minor changes |
| Copy-MgUserOnenoteNotebook | Minor changes |
| Copy-MgUserOnenotePageToSection | Minor changes |
| Copy-MgUserOnenoteSectionToNotebook | Minor changes |
| Copy-MgUserOnenoteSectionToSectionGroup | Minor changes |
| Disable-MgDeviceManagementManagedDeviceLostMode | Minor changes |
| Disable-MgUserAuthenticationPhoneMethodSmsSignIn | Minor changes |
| Disable-MgUserManagedDeviceLostMode | Minor changes |
| Disconnect-MgDeviceManagementRemoteAssistancePartner | Minor changes |
| Enable-MgUserAuthenticationPhoneMethodSmsSignIn | Minor changes |
| Find-MgDeviceManagementManagedDevice | Minor changes |
| Find-MgUserManagedDevice | Minor changes |
| Get-MgAdminEdgeInternetExplorerModeSiteList | Minor changes |
| Get-MgAdminPeopleProfileCardProperty | Minor changes |
| Get-MgAgreement | Minor changes |
| Get-MgAgreementAcceptance | Minor changes |
| Get-MgAgreementFile | Minor changes |
| Get-MgAllGroupTeamChannel | Minor changes |
| Get-MgAppCatalogTeamAppDefinition | Minor changes |
| Get-MgApplicationFederatedIdentityCredential | Minor changes |
| Get-MgApplicationOwnerAsEndpoint | Minor changes |
| Get-MgApplicationOwnerAsUser | Minor changes |
| Get-MgApplicationSynchronizationTemplate | Minor changes |
| Get-MgAuditLogDirectoryAudit | Minor changes |
| Get-MgBookingBusinessService | Minor changes |
| Get-MgBookingBusinessStaffMember | Minor changes |
| Get-MgChatMember | Minor changes |
| Get-MgChatMessage | Minor changes |
| Get-MgChatMessageCount | Minor changes |
| Get-MgChatMessageDelta | Minor changes |
| Get-MgChatMessageHostedContent | Minor changes |
| Get-MgChatMessageHostedContentCount | Minor changes |
| Get-MgChatMessageReply | Minor changes |
| Get-MgChatPermissionGrant | Minor changes |
| Get-MgChatRetainedMessage | Minor changes |
| Get-MgCommunicationCallRecordParticipantV2 | Minor changes |
| Get-MgCommunicationOnlineMeetingAttendanceReport | Minor changes |
| Get-MgCommunicationOnlineMeetingAttendanceReportAttendanceRecord | Minor changes |
| Get-MgCommunicationOnlineMeetingTranscript | Minor changes |
| Get-MgContact | Minor changes |
| Get-MgContactDirectReportAsOrgContact | Minor changes |
| Get-MgDevice | Minor changes |
| Get-MgDeviceAppManagementDefaultManagedAppProtection | Minor changes |
| Get-MgDeviceAppManagementManagedAppRegistrationOperation | Minor changes |
| Get-MgDeviceAppManagementManagedEBook | Minor changes |
| Get-MgDeviceAppManagementManagedEBookAssignment | Minor changes |
| Get-MgDeviceAppManagementManagedEBookDeviceState | Minor changes |
| Get-MgDeviceAppManagementManagedEBookUserStateSummaryDeviceState | Minor changes |
| Get-MgDeviceAppManagementMdmWindowsInformationProtectionPolicyAssignment | Minor changes |
| Get-MgDeviceAppManagementMdmWindowsInformationProtectionPolicyExemptAppLockerFile | Minor changes |
| Get-MgDeviceAppManagementMdmWindowsInformationProtectionPolicyProtectedAppLockerFile | Minor changes |
| Get-MgDeviceAppManagementMobileApp | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsAndroidLobAppCategory | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsAndroidStoreApp | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsAndroidStoreAppAssignment | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsMacOSDmgAppContentVersionContainedApp | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsMacOSDmgAppContentVersionFile | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsMacOSLobAppCategory | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsManagedAndroidLobAppAssignment | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsManagedAndroidLobAppContentVersionFile | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsManagedMobileLobAppCategory | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsManagedMobileLobAppContentVersion | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsManagedMobileLobAppContentVersionFile | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsManagediOSLobAppAssignment | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsManagediOSLobAppContentVersionFile | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsMicrosoftStoreForBusinessAppCategory | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsWin32LobApp | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsWin32LobAppCategory | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsWin32LobAppContentVersion | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsWin32LobAppContentVersionFile | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsWindowsAppXAssignment | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsWindowsAppXContentVersionContainedApp | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsWindowsAppXContentVersionFile | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsWindowsMobileMsiContentVersion | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsWindowsMobileMsiContentVersionFile | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsWindowsUniversalAppXCategory | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsWindowsUniversalAppXContentVersion | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsWindowsWebApp | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsWindowsWebAppAssignment | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsWindowsWebAppCategory | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsiOSLobAppContentVersionContainedApp | Minor changes |
| Get-MgDeviceAppManagementMobileAppAsiOSLobAppContentVersionFile | Minor changes |
| Get-MgDeviceAppManagementMobileAppCategory | Minor changes |
| Get-MgDeviceAppManagementMobileAppConfiguration | Minor changes |
| Get-MgDeviceAppManagementMobileAppConfigurationAssignment | Minor changes |
| Get-MgDeviceAppManagementTargetedManagedAppConfigurationAssignment | Minor changes |
| Get-MgDeviceAppManagementVppToken | Minor changes |
| Get-MgDeviceAppManagementWindowsInformationProtectionPolicyExemptAppLockerFile | Minor changes |
| Get-MgDeviceAppManagementiOSManagedAppProtection | Minor changes |
| Get-MgDeviceAppManagementiOSManagedAppProtectionApp | Minor changes |
| Get-MgDeviceManagement | Minor changes |
| Get-MgDeviceManagementAuditEventAuditActivityType | Minor changes |
| Get-MgDeviceManagementAuditEventAuditCategory | Minor changes |
| Get-MgDeviceManagementComplianceManagementPartner | Minor changes |
| Get-MgDeviceManagementDeviceCompliancePolicy | Minor changes |
| Get-MgDeviceManagementDeviceCompliancePolicyAssignment | Minor changes |
| Get-MgDeviceManagementDeviceCompliancePolicyDeviceSettingStateSummary | Minor changes |
| Get-MgDeviceManagementDeviceCompliancePolicyScheduledActionForRuleScheduledActionConfiguration | Minor changes |
| Get-MgDeviceManagementDeviceCompliancePolicySettingStateSummary | Minor changes |
| Get-MgDeviceManagementDeviceConfiguration | Minor changes |
| Get-MgDeviceManagementDeviceConfigurationOmaSettingPlainTextValue | Minor changes |
| Get-MgDeviceManagementExchangeConnector | Minor changes |
| Get-MgDeviceManagementIoUpdateStatus | Minor changes |
| Get-MgDeviceManagementManagedDevice | Minor changes |
| Get-MgDeviceManagementManagedDeviceCompliancePolicyState | Minor changes |
| Get-MgDeviceManagementMobileAppTroubleshootingEvent | Minor changes |
| Get-MgDeviceManagementMobileAppTroubleshootingEventAppLogCollectionRequest | Minor changes |
| Get-MgDeviceManagementMobileThreatDefenseConnector | Minor changes |
| Get-MgDeviceManagementNotificationMessageTemplate | Minor changes |
| Get-MgDeviceManagementNotificationMessageTemplateLocalizedNotificationMessage | Minor changes |
| Get-MgDeviceManagementPartner | Minor changes |
| Get-MgDeviceManagementReportCachedReport | Minor changes |
| Get-MgDeviceManagementReportCompliancePolicyNonComplianceReport | Minor changes |
| Get-MgDeviceManagementReportCompliancePolicyNonComplianceSummaryReport | Minor changes |
| Get-MgDeviceManagementReportComplianceSettingNonComplianceReport | Minor changes |
| Get-MgDeviceManagementReportConfigurationPolicyNonComplianceReport | Minor changes |
| Get-MgDeviceManagementReportConfigurationPolicyNonComplianceSummaryReport | Minor changes |
| Get-MgDeviceManagementReportConfigurationSettingNonComplianceReport | Minor changes |
| Get-MgDeviceManagementReportDeviceManagementIntentPerSettingContributingProfile | Minor changes |
| Get-MgDeviceManagementReportDeviceManagementIntentSettingReport | Minor changes |
| Get-MgDeviceManagementReportDeviceNonComplianceReport | Minor changes |
| Get-MgDeviceManagementReportDeviceWithoutCompliancePolicyReport | Minor changes |
| Get-MgDeviceManagementReportExportJob | Minor changes |
| Get-MgDeviceManagementReportFilter | Minor changes |
| Get-MgDeviceManagementReportHistoricalReport | Minor changes |
| Get-MgDeviceManagementReportNoncompliantDeviceAndSettingReport | Minor changes |
| Get-MgDeviceManagementReportPolicyNonComplianceMetadata | Minor changes |
| Get-MgDeviceManagementReportPolicyNonComplianceReport | Minor changes |
| Get-MgDeviceManagementReportPolicyNonComplianceSummaryReport | Minor changes |
| Get-MgDeviceManagementReportSettingNonComplianceReport | Minor changes |
| Get-MgDeviceManagementResourceOperation | Minor changes |
| Get-MgDeviceManagementRoleAssignment | Minor changes |
| Get-MgDeviceManagementUserExperienceAnalyticAppHealthApplicationPerformanceByOsversion | Minor changes |
| Get-MgDeviceManagementUserExperienceAnalyticAppHealthOSVersionPerformance | Minor changes |
| Get-MgDeviceManagementUserExperienceAnalyticAppHealthOverviewMetricValue | Minor changes |
| Get-MgDeviceManagementUserExperienceAnalyticBaseline | Minor changes |
| Get-MgDeviceManagementUserExperienceAnalyticCategory | Minor changes |
| Get-MgDeviceManagementUserExperienceAnalyticDevicePerformance | Minor changes |
| Get-MgDeviceManagementUserExperienceAnalyticDeviceStartupProcess | Minor changes |
| Get-MgDeviceManagementUserExperienceAnalyticMetricHistory | Minor changes |
| Get-MgDeviceManagementUserExperienceAnalyticScoreHistory | Minor changes |
| Get-MgDeviceManagementUserExperienceAnalyticWorkFromAnywhereMetric | Minor changes |
| Get-MgDeviceManagementUserExperienceAnalyticWorkFromAnywhereModelPerformance | Minor changes |
| Get-MgDeviceManagementVirtualEndpointAuditEventAuditActivityType | Minor changes |
| Get-MgDeviceManagementVirtualEndpointCloudPc | Minor changes |
| Get-MgDeviceManagementVirtualEndpointDeviceImageSourceImage | Minor changes |
| Get-MgDeviceManagementVirtualEndpointGalleryImage | Minor changes |
| Get-MgDeviceManagementVirtualEndpointProvisioningPolicy | Minor changes |
| Get-MgDeviceManagementVirtualEndpointProvisioningPolicyAssignment | Minor changes |
| Get-MgDeviceManagementVirtualEndpointProvisioningPolicyAssignmentAssignedUser | Minor changes |
| Get-MgDeviceManagementVirtualEndpointUserSettingAssignment | Minor changes |
| Get-MgDeviceManagementWindowsMalwareInformation | Minor changes |
| Get-MgDeviceManagementWindowsMalwareInformationDeviceMalwareState | Minor changes |
| Get-MgDeviceMemberOf | Minor changes |
| Get-MgDeviceRegisteredOwnerAsEndpoint | Minor changes |
| Get-MgDeviceRegisteredUserAsAppRoleAssignment | Minor changes |
| Get-MgDeviceRegisteredUserAsEndpoint | Minor changes |
| Get-MgDeviceTransitiveMemberOfAsGroup | Minor changes |
| Get-MgDirectoryAdministrativeUnitExtension | Minor changes |
| Get-MgDirectoryAdministrativeUnitMemberAsApplication | Minor changes |
| Get-MgDirectoryAdministrativeUnitMemberAsGroup | Minor changes |
| Get-MgDirectoryDeletedItemAsServicePrincipal | Minor changes |
| Get-MgDirectoryDeletedItemAsUser | Minor changes |
| Get-MgDirectoryOnPremiseSynchronization | Minor changes |
| Get-MgDirectoryRoleMemberAsGroup | Minor changes |
| Get-MgDirectoryRoleMemberAsUser | Minor changes |
| Get-MgDirectoryRoleScopedMember | Minor changes |
| Get-MgDomain | Minor changes |
| Get-MgDomainRootDomain | Minor changes |
| Get-MgDomainServiceConfigurationRecord | Minor changes |
| Get-MgDrive | Minor changes |
| Get-MgDriveFollowing | Minor changes |
| Get-MgDriveItemListItemDocumentSetVersion | Minor changes |
| Get-MgDriveItemPermission | Minor changes |
| Get-MgDriveListColumn | Minor changes |
| Get-MgDriveListContentType | Minor changes |
| Get-MgDriveListItemDocumentSetVersion | Minor changes |
| Get-MgDriveRootChild | Minor changes |
| Get-MgDriveRootListItemDocumentSetVersion | Minor changes |
| Get-MgDriveRootListItemVersion | Minor changes |
| Get-MgDriveRootSubscription | Minor changes |
| Get-MgDriveRootVersion | Minor changes |
| Get-MgEducationClassAssignmentSettingGradingCategory | Minor changes |
| Get-MgEducationClassAssignmentSubmission | Minor changes |
| Get-MgEducationClassAssignmentSubmissionOutcome | Minor changes |
| Get-MgEducationClassModuleResource | Minor changes |
| Get-MgEducationMeAssignment | Minor changes |
| Get-MgEducationMeAssignmentResource | Minor changes |
| Get-MgEducationMeAssignmentSubmission | Minor changes |
| Get-MgEducationUserAssignmentResource | Minor changes |
| Get-MgEducationUserAssignmentSubmission | Minor changes |
| Get-MgEducationUserAssignmentSubmissionOutcome | Minor changes |
| Get-MgEducationUserAssignmentSubmissionSubmittedResource | Minor changes |
| Get-MgEducationUserClass | Minor changes |
| Get-MgEducationUserSchool | Minor changes |
| Get-MgEntitlementManagementAccessPackageIncompatibleWith | Minor changes |
| Get-MgEntitlementManagementAssignment | Minor changes |
| Get-MgEntitlementManagementAssignmentPolicyCustomExtensionStageSetting | Minor changes |
| Get-MgEntitlementManagementAssignmentRequest | Minor changes |
| Get-MgEntitlementManagementCatalogCustomWorkflowExtension | Minor changes |
| Get-MgEntitlementManagementCatalogResourceRole | Minor changes |
| Get-MgEntitlementManagementConnectedOrganization | Minor changes |
| Get-MgEntitlementManagementResource | Minor changes |
| Get-MgEntitlementManagementResourceEnvironment | Minor changes |
| Get-MgEntitlementManagementResourceEnvironmentResourceRoleResourceScope | Minor changes |
| Get-MgEntitlementManagementResourceEnvironmentResourceScopeResourceRole | Minor changes |
| Get-MgEntitlementManagementResourceRequest | Minor changes |
| Get-MgEntitlementManagementResourceRequestCatalogCustomWorkflowExtension | Minor changes |
| Get-MgEntitlementManagementResourceRequestCatalogResource | Minor changes |
| Get-MgEntitlementManagementResourceRequestCatalogResourceRoleResourceScope | Minor changes |
| Get-MgEntitlementManagementResourceRequestCatalogResourceScopeResourceRole | Minor changes |
| Get-MgEntitlementManagementResourceRequestCatalogResourceScopeResourceRoleResourceScope | Minor changes |
| Get-MgEntitlementManagementResourceRequestResourceRole | Minor changes |
| Get-MgEntitlementManagementResourceRequestResourceScope | Minor changes |
| Get-MgEntitlementManagementResourceRole | Minor changes |
| Get-MgEntitlementManagementResourceRoleResourceScope | Minor changes |
| Get-MgEntitlementManagementResourceRoleScopeResourceRole | Minor changes |
| Get-MgEntitlementManagementResourceRoleScopeRoleResourceScope | Minor changes |
| Get-MgEntitlementManagementResourceRoleScopeRoleResourceScopeResourceRole | Minor changes |
| Get-MgEntitlementManagementResourceScope | Minor changes |
| Get-MgExternalConnection | Minor changes |
| Get-MgExternalConnectionGroup | Minor changes |
| Get-MgExternalConnectionGroupMember | Minor changes |
| Get-MgExternalConnectionItem | Minor changes |
| Get-MgExternalConnectionOperation | Minor changes |
| Get-MgGroupAppRoleAssignment | Minor changes |
| Get-MgGroupCalendarSchedule | Minor changes |
| Get-MgGroupConversationThread | Minor changes |
| Get-MgGroupConversationThreadPostExtension | Minor changes |
| Get-MgGroupDrive | Minor changes |
| Get-MgGroupDriveContentTypeBaseType | Minor changes |
| Get-MgGroupDriveItem | Minor changes |
| Get-MgGroupDriveItemActivityByInterval | Minor changes |
| Get-MgGroupDriveItemAnalyticItemActivityStat | Minor changes |
| Get-MgGroupDriveItemDelta | Minor changes |
| Get-MgGroupDriveItemListItemActivityByInterval | Minor changes |
| Get-MgGroupDriveItemListItemVersion | Minor changes |
| Get-MgGroupDriveItemPermission | Minor changes |
| Get-MgGroupDriveListColumn | Minor changes |
| Get-MgGroupDriveListContentTypeColumnLink | Minor changes |
| Get-MgGroupDriveListContentTypeColumnPosition | Minor changes |
| Get-MgGroupDriveListContentTypeCompatibleHubContentType | Minor changes |
| Get-MgGroupDriveListItemActivityByInterval | Minor changes |
| Get-MgGroupDriveListItemDelta | Minor changes |
| Get-MgGroupDriveListItemVersion | Minor changes |
| Get-MgGroupDriveListOperation | Minor changes |
| Get-MgGroupDriveRootActivityByInterval | Minor changes |
| Get-MgGroupDriveRootAnalyticItemActivityStat | Minor changes |
| Get-MgGroupDriveRootDelta | Minor changes |
| Get-MgGroupDriveRootListItemActivityByInterval | Minor changes |
| Get-MgGroupDriveRootListItemDocumentSetVersion | Minor changes |
| Get-MgGroupDriveRootPermission | Minor changes |
| Get-MgGroupDriveRootThumbnail | Minor changes |
| Get-MgGroupDriveSpecial | Minor changes |
| Get-MgGroupEventAttachment | Minor changes |
| Get-MgGroupEventDelta | Minor changes |
| Get-MgGroupExtension | Minor changes |
| Get-MgGroupMemberAsApplication | Minor changes |
| Get-MgGroupMemberAsGroup | Minor changes |
| Get-MgGroupMemberAsOrgContact | Minor changes |
| Get-MgGroupMemberAsUser | Minor changes |
| Get-MgGroupMemberOf | Minor changes |
| Get-MgGroupMemberOfAsAdministrativeUnit | Minor changes |
| Get-MgGroupMemberWithLicenseErrorAsApplication | Minor changes |
| Get-MgGroupMemberWithLicenseErrorAsUser | Minor changes |
| Get-MgGroupOnenoteNotebookFromWebUrl | Minor changes |
| Get-MgGroupOnenoteNotebookSection | Minor changes |
| Get-MgGroupOnenoteNotebookSectionGroup | Minor changes |
| Get-MgGroupOnenoteSectionPage | Minor changes |
| Get-MgGroupOwnerAsApplication | Minor changes |
| Get-MgGroupOwnerAsDevice | Minor changes |
| Get-MgGroupOwnerAsUser | Minor changes |
| Get-MgGroupPermissionGrant | Minor changes |
| Get-MgGroupPlannerPlan | Minor changes |
| Get-MgGroupSetting | Minor changes |
| Get-MgGroupSettingTemplateGroupSettingTemplate | Minor changes |
| Get-MgGroupSite | Minor changes |
| Get-MgGroupSiteActivityByInterval | Minor changes |
| Get-MgGroupSiteApplicableContentTypeForList | Minor changes |
| Get-MgGroupSiteByPath | Minor changes |
| Get-MgGroupSiteContentTypeBaseType | Minor changes |
| Get-MgGroupSiteContentTypeColumn | Minor changes |
| Get-MgGroupSiteContentTypeCompatibleHubContentType | Minor changes |
| Get-MgGroupSiteDelta | Minor changes |
| Get-MgGroupSiteDrive | Minor changes |
| Get-MgGroupSiteGetByPathDrive | Minor changes |
| Get-MgGroupSiteItem | Minor changes |
| Get-MgGroupSiteList | Minor changes |
| Get-MgGroupSiteListContentType | Minor changes |
| Get-MgGroupSiteListContentTypeColumn | Minor changes |
| Get-MgGroupSiteListContentTypeCompatibleHubContentType | Minor changes |
| Get-MgGroupSiteListItemActivityByInterval | Minor changes |
| Get-MgGroupSiteListItemDelta | Minor changes |
| Get-MgGroupSiteListItemDocumentSetVersion | Minor changes |
| Get-MgGroupSiteListSubscription | Minor changes |
| Get-MgGroupSiteOnenoteNotebookSectionGroup | Minor changes |
| Get-MgGroupSiteOnenoteNotebookSectionGroupSection | Minor changes |
| Get-MgGroupSiteOnenoteNotebookSectionPage | Minor changes |
| Get-MgGroupSiteOnenotePage | Minor changes |
| Get-MgGroupSiteOnenoteResource | Minor changes |
| Get-MgGroupSiteOnenoteSection | Minor changes |
| Get-MgGroupSiteOnenoteSectionGroupSectionPage | Minor changes |
| Get-MgGroupSitePageAsSitePageCanvaLayoutHorizontalSection | Minor changes |
| Get-MgGroupSitePageAsSitePageCanvaLayoutVerticalSectionWebpart | Minor changes |
| Get-MgGroupSitePageAsSitePageWebPart | Minor changes |
| Get-MgGroupSitePageMicrosoftGraphSitePageCanvaLayoutHorizontalSectionColumnWebpartPositionOfWebPart | Minor changes |
| Get-MgGroupSitePageMicrosoftGraphSitePageCanvaLayoutVerticalSectionWebpartPositionOfWebPart | Minor changes |
| Get-MgGroupSitePageMicrosoftGraphSitePageWebPartPositionOfWebPart | Minor changes |
| Get-MgGroupSiteTermStore | Minor changes |
| Get-MgGroupSiteTermStoreGroupSet | Minor changes |
| Get-MgGroupSiteTermStoreGroupSetChild | Minor changes |
| Get-MgGroupSiteTermStoreGroupSetChildRelation | Minor changes |
| Get-MgGroupSiteTermStoreGroupSetRelation | Minor changes |
| Get-MgGroupSiteTermStoreGroupSetTermChild | Minor changes |
| Get-MgGroupSiteTermStoreGroupSetTermChildRelation | Minor changes |
| Get-MgGroupSiteTermStoreGroupSetTermRelation | Minor changes |
| Get-MgGroupSiteTermStoreSetParentGroupSetChild | Minor changes |
| Get-MgGroupSiteTermStoreSetParentGroupSetChildRelation | Minor changes |
| Get-MgGroupSiteTermStoreSetParentGroupSetTermChild | Minor changes |
| Get-MgGroupSiteTermStoreSetParentGroupSetTermRelation | Minor changes |
| Get-MgGroupSiteTermStoreSetRelation | Minor changes |
| Get-MgGroupSiteTermStoreSetTerm | Minor changes |
| Get-MgGroupTeamChannelMember | Minor changes |
| Get-MgGroupTeamChannelMessageReplyHostedContent | Minor changes |
| Get-MgGroupTeamChannelSharedWithTeam | Minor changes |
| Get-MgGroupTeamIncomingChannel | Minor changes |
| Get-MgGroupTeamOperation | Minor changes |
| Get-MgGroupTeamPrimaryChannelMember | Minor changes |
| Get-MgGroupTeamPrimaryChannelMessage | Minor changes |
| Get-MgGroupTeamPrimaryChannelMessageReply | Minor changes |
| Get-MgGroupTeamPrimaryChannelMessageReplyHostedContent | Minor changes |
| Get-MgGroupTeamPrimaryChannelSharedWithTeam | Minor changes |
| Get-MgGroupTeamPrimaryChannelSharedWithTeamAllowedMember | Minor changes |
| Get-MgGroupTeamScheduleOpenShift | Minor changes |
| Get-MgGroupTeamScheduleOpenShiftChangeRequest | Minor changes |
| Get-MgGroupTeamTagMember | Minor changes |
| Get-MgGroupThreadPostExtension | Minor changes |
| Get-MgGroupTransitiveMember | Minor changes |
| Get-MgGroupTransitiveMemberAsApplication | Minor changes |
| Get-MgGroupTransitiveMemberAsDevice | Minor changes |
| Get-MgGroupTransitiveMemberAsGroup | Minor changes |
| Get-MgGroupTransitiveMemberAsOrgContact | Minor changes |
| Get-MgGroupTransitiveMemberAsServicePrincipal | Minor changes |
| Get-MgGroupTransitiveMemberOf | Minor changes |
| Get-MgGroupTransitiveMemberOfAsGroup | Minor changes |
| Get-MgIdentityApiConnector | Minor changes |
| Get-MgIdentityAuthenticationEventFlow | Minor changes |
| Get-MgIdentityB2XUserFlow | Minor changes |
| Get-MgIdentityB2XUserFlowLanguageOverridePage | Minor changes |
| Get-MgIdentityConditionalAccessAuthenticationContextClassReference | Minor changes |
| Get-MgIdentityConditionalAccessNamedLocation | Minor changes |
| Get-MgIdentityConditionalAccessPolicy | Minor changes |
| Get-MgIdentityConditionalAccessTemplate | Minor changes |
| Get-MgIdentityCustomAuthenticationExtension | Minor changes |
| Get-MgIdentityGovernanceAccessReviewDefinition | Minor changes |
| Get-MgIdentityGovernanceAccessReviewDefinitionInstance | Minor changes |
| Get-MgIdentityGovernanceAccessReviewDefinitionInstanceDecision | Minor changes |
| Get-MgIdentityGovernanceAccessReviewDefinitionInstanceDecisionInsight | Minor changes |
| Get-MgIdentityGovernanceAccessReviewDefinitionInstanceStageDecisionInsight | Minor changes |
| Get-MgIdentityGovernanceAccessReviewHistoryDefinitionInstance | Minor changes |
| Get-MgIdentityGovernanceAppConsentRequest | Minor changes |
| Get-MgIdentityGovernanceAppConsentRequestUserConsentRequestApprovalStage | Minor changes |
| Get-MgIdentityGovernanceLifecycleWorkflowCustomTaskExtension | Minor changes |
| Get-MgIdentityGovernanceLifecycleWorkflowDeletedItemWorkflowUserProcessingResult | Minor changes |
| Get-MgIdentityGovernanceLifecycleWorkflowDeletedItemWorkflowVersion | Minor changes |
| Get-MgIdentityGovernanceLifecycleWorkflowExecutionScope | Minor changes |
| Get-MgIdentityGovernanceLifecycleWorkflowRun | Minor changes |
| Get-MgIdentityGovernanceLifecycleWorkflowRunUserProcessingResult | Minor changes |
| Get-MgIdentityGovernanceLifecycleWorkflowTaskReport | Minor changes |
| Get-MgIdentityGovernanceLifecycleWorkflowTemplateTaskProcessingResult | Minor changes |
| Get-MgIdentityGovernancePrivilegedAccessGroupAssignmentApproval | Minor changes |
| Get-MgIdentityGovernancePrivilegedAccessGroupAssignmentSchedule | Minor changes |
| Get-MgIdentityGovernancePrivilegedAccessGroupAssignmentScheduleInstance | Minor changes |
| Get-MgIdentityGovernancePrivilegedAccessGroupAssignmentScheduleRequest | Minor changes |
| Get-MgIdentityGovernancePrivilegedAccessGroupEligibilityScheduleInstance | Minor changes |
| Get-MgIdentityGovernancePrivilegedAccessGroupEligibilityScheduleRequest | Minor changes |
| Get-MgIdentityGovernanceTermsOfUseAgreementAcceptance | Minor changes |
| Get-MgIdentityGovernanceTermsOfUseAgreementFile | Minor changes |
| Get-MgIdentityGovernanceTermsOfUseAgreementFileLocalization | Minor changes |
| Get-MgIdentityGovernanceTermsOfUseAgreementFileLocalizationVersion | Minor changes |
| Get-MgInformationProtectionThreatAssessmentRequestResult | Minor changes |
| Get-MgInvitationInvitedUserSponsor | Minor changes |
| Get-MgOrganization | Minor changes |
| Get-MgOrganizationBrandingLocalization | Minor changes |
| Get-MgOrganizationCertificateBasedAuthConfiguration | Minor changes |
| Get-MgOrganizationCount | Minor changes |
| Get-MgPlannerBucket | Minor changes |
| Get-MgPlannerPlan | Minor changes |
| Get-MgPlannerTask | Minor changes |
| Get-MgPolicyActivityBasedTimeoutPolicy | Minor changes |
| Get-MgPolicyActivityBasedTimeoutPolicyApplyTo | Minor changes |
| Get-MgPolicyAppManagementPolicy | Minor changes |
| Get-MgPolicyAuthenticationMethodPolicy | Minor changes |
| Get-MgPolicyAuthenticationStrengthPolicy | Minor changes |
| Get-MgPolicyAuthenticationStrengthPolicyCombinationConfiguration | Minor changes |
| Get-MgPolicyRoleManagementPolicy | Minor changes |
| Get-MgPolicyRoleManagementPolicyAssignment | Minor changes |
| Get-MgPolicyRoleManagementPolicyRule | Minor changes |
| Get-MgPolicyTokenIssuancePolicy | Minor changes |
| Get-MgPolicyTokenLifetimePolicy | Minor changes |
| Get-MgPrintConnector | Minor changes |
| Get-MgPrintPrinterJobTask | Minor changes |
| Get-MgPrintPrinterShare | Minor changes |
| Get-MgPrintService | Minor changes |
| Get-MgPrintServiceCount | Minor changes |
| Get-MgPrintServiceEndpoint | Minor changes |
| Get-MgPrintServiceEndpointCount | Minor changes |
| Get-MgPrintShareJob | Minor changes |
| Get-MgPrintShareJobTask | Minor changes |
| Get-MgPrintTaskDefinitionTask | Minor changes |
| Get-MgPrivacySubjectRightsRequestApprover | Minor changes |
| Get-MgPrivacySubjectRightsRequestCollaborator | Minor changes |
| Get-MgPrivacySubjectRightsRequestNote | Minor changes |
| Get-MgReportAuthenticationMethodUserRegistrationDetail | Minor changes |
| Get-MgReportMonthlyPrintUsageByPrinter | Minor changes |
| Get-MgReportMonthlyPrintUsageByUser | Minor changes |
| Get-MgReportPartnerBillingOperation | Minor changes |
| Get-MgRiskyServicePrincipalHistory | Minor changes |
| Get-MgRiskyUserHistory | Minor changes |
| Get-MgRoleManagementDirectoryResourceNamespace | Minor changes |
| Get-MgRoleManagementDirectoryRoleDefinition | Minor changes |
| Get-MgRoleManagementDirectoryRoleDefinitionInheritPermissionFrom | Minor changes |
| Get-MgRoleManagementEntitlementManagementRoleAssignment | Minor changes |
| Get-MgRoleManagementEntitlementManagementRoleAssignmentScheduleRequest | Minor changes |
| Get-MgSchemaExtension | Minor changes |
| Get-MgSearchQna | Minor changes |
| Get-MgSecurityAlert | Minor changes |
| Get-MgSecurityAttackSimulation | Minor changes |
| Get-MgSecurityAttackSimulationAutomation | Minor changes |
| Get-MgSecurityAttackSimulationAutomationRun | Minor changes |
| Get-MgSecurityAttackSimulationEndUserNotification | Minor changes |
| Get-MgSecurityAttackSimulationEndUserNotificationDetail | Minor changes |
| Get-MgSecurityAttackSimulationLoginPage | Minor changes |
| Get-MgSecurityAttackSimulationOperation | Minor changes |
| Get-MgSecurityAttackSimulationPayload | Minor changes |
| Get-MgSecurityAttackSimulationTraining | Minor changes |
| Get-MgSecurityAttackSimulationTrainingLanguageDetail | Minor changes |
| Get-MgSecurityCaseEdiscoveryCaseCustodianSiteSource | Minor changes |
| Get-MgSecurityCaseEdiscoveryCaseCustodianUnifiedGroupSource | Minor changes |
| Get-MgSecurityCaseEdiscoveryCaseOperation | Minor changes |
| Get-MgSecurityCaseEdiscoveryCaseReviewSet | Minor changes |
| Get-MgSecurityCaseEdiscoveryCaseReviewSetQuery | Minor changes |
| Get-MgSecurityCaseEdiscoveryCaseSearch | Minor changes |
| Get-MgSecurityCaseEdiscoveryCaseSearchCustodianSource | Minor changes |
| Get-MgSecurityCaseEdiscoveryCaseSearchNoncustodialSource | Minor changes |
| Get-MgSecurityCaseEdiscoveryCaseTag | Minor changes |
| Get-MgSecurityCaseEdiscoveryCaseTagChildTag | Minor changes |
| Get-MgSecurityLabelCitation | Minor changes |
| Get-MgSecurityLabelRetentionLabel | Minor changes |
| Get-MgSecurityLabelRetentionLabelDispositionReviewStage | Minor changes |
| Get-MgSecuritySubjectRightsRequest | Minor changes |
| Get-MgSecuritySubjectRightsRequestCollaborator | Minor changes |
| Get-MgSecurityThreatIntelligenceHost | Minor changes |
| Get-MgSecurityThreatIntelligenceHostChildHostPair | Minor changes |
| Get-MgSecurityThreatIntelligenceHostParentHostPair | Minor changes |
| Get-MgSecurityThreatIntelligenceHostPassiveDns | Minor changes |
| Get-MgSecurityThreatIntelligenceHostPassiveDnsReverse | Minor changes |
| Get-MgSecurityThreatIntelligenceHostPort | Minor changes |
| Get-MgSecurityThreatIntelligenceHostSubdomain | Minor changes |
| Get-MgSecurityThreatIntelligenceHostTracker | Minor changes |
| Get-MgSecurityThreatIntelligenceIntelProfileIndicator | Minor changes |
| Get-MgSecurityThreatIntelligencePassiveDnsRecord | Minor changes |
| Get-MgSecurityThreatIntelligenceSslCertificate | Minor changes |
| Get-MgSecurityThreatIntelligenceWhoisRecord | Minor changes |
| Get-MgSecurityTriggerRetentionEvent | Minor changes |
| Get-MgServiceAnnouncementHealthOverview | Minor changes |
| Get-MgServiceAnnouncementMessage | Minor changes |
| Get-MgServicePrincipal | Minor changes |
| Get-MgServicePrincipalAppManagementPolicy | Minor changes |
| Get-MgServicePrincipalAppRoleAssignment | Minor changes |
| Get-MgServicePrincipalCreatedObject | Minor changes |
| Get-MgServicePrincipalEndpoint | Minor changes |
| Get-MgServicePrincipalMemberOf | Minor changes |
| Get-MgServicePrincipalMemberOfAsAdministrativeUnit | Minor changes |
| Get-MgServicePrincipalMemberOfAsDirectoryRole | Minor changes |
| Get-MgServicePrincipalMemberOfAsGroup | Minor changes |
| Get-MgServicePrincipalOauth2PermissionGrant | Minor changes |
| Get-MgServicePrincipalOwnedObject | Minor changes |
| Get-MgServicePrincipalOwnedObjectAsApplication | Minor changes |
| Get-MgServicePrincipalOwnedObjectAsEndpoint | Minor changes |
| Get-MgServicePrincipalOwnedObjectAsGroup | Minor changes |
| Get-MgServicePrincipalOwnedObjectAsServicePrincipal | Minor changes |
| Get-MgServicePrincipalOwnerAsAppRoleAssignment | Minor changes |
| Get-MgServicePrincipalOwnerAsEndpoint | Minor changes |
| Get-MgServicePrincipalOwnerAsServicePrincipal | Minor changes |
| Get-MgServicePrincipalOwnerAsUser | Minor changes |
| Get-MgServicePrincipalRiskDetection | Minor changes |
| Get-MgServicePrincipalSynchronizationJob | Minor changes |
| Get-MgServicePrincipalSynchronizationJobSchemaDirectory | Minor changes |
| Get-MgServicePrincipalTokenLifetimePolicy | Minor changes |
| Get-MgShareContentTypeBaseType | Minor changes |
| Get-MgShareListContentTypeColumnLink | Minor changes |
| Get-MgShareListItem | Minor changes |
| Get-MgShareListSubscription | Minor changes |
| Get-MgSiteAnalyticItemActivityStat | Minor changes |
| Get-MgSiteColumn | Minor changes |
| Get-MgSiteContentTypeColumn | Minor changes |
| Get-MgSiteContentTypeColumnLink | Minor changes |
| Get-MgSiteGetByPathDrive | Minor changes |
| Get-MgSiteListColumn | Minor changes |
| Get-MgSiteListContentTypeColumnLink | Minor changes |
| Get-MgSiteListContentTypeColumnPosition | Minor changes |
| Get-MgSiteListOperation | Minor changes |
| Get-MgSiteOnenoteNotebook | Minor changes |
| Get-MgSiteOnenoteNotebookFromWebUrl | Minor changes |
| Get-MgSiteOnenoteNotebookSection | Minor changes |
| Get-MgSiteOnenoteNotebookSectionGroup | Minor changes |
| Get-MgSiteOnenotePage | Minor changes |
| Get-MgSiteOnenoteSection | Minor changes |
| Get-MgSiteOnenoteSectionPage | Minor changes |
| Get-MgSiteOperation | Minor changes |
| Get-MgSitePage | Minor changes |
| Get-MgSitePageAsSitePage | Minor changes |
| Get-MgSitePageAsSitePageCanvaLayoutHorizontalSection | Minor changes |
| Get-MgSitePageAsSitePageCanvaLayoutVerticalSectionWebpart | Minor changes |
| Get-MgSitePageAsSitePageWebPart | Minor changes |
| Get-MgSiteTermStore | Minor changes |
| Get-MgSiteTermStoreGroupSet | Minor changes |
| Get-MgSiteTermStoreGroupSetChildRelation | Minor changes |
| Get-MgSiteTermStoreGroupSetTermChild | Minor changes |
| Get-MgSiteTermStoreGroupSetTermChildRelation | Minor changes |
| Get-MgSiteTermStoreSet | Minor changes |
| Get-MgSiteTermStoreSetChild | Minor changes |
| Get-MgSiteTermStoreSetChildRelation | Minor changes |
| Get-MgSiteTermStoreSetParentGroupSet | Minor changes |
| Get-MgSiteTermStoreSetParentGroupSetChild | Minor changes |
| Get-MgSiteTermStoreSetParentGroupSetTermChild | Minor changes |
| Get-MgSiteTermStoreSetTerm | Minor changes |
| Get-MgSiteTermStoreSetTermChild | Minor changes |
| Get-MgSiteTermStoreSetTermChildRelation | Minor changes |
| Get-MgSolutionBackupRestoreExchangeRestoreSession | Minor changes |
| Get-MgSolutionBackupRestoreMailboxInclusionRule | Minor changes |
| Get-MgSolutionBackupRestoreOneDriveForBusinessProtectionPolicyDriveProtectionUnit | Minor changes |
| Get-MgSolutionBackupRestoreProtectionPolicy | Minor changes |
| Get-MgSolutionBackupRestoreProtectionUnit | Minor changes |
| Get-MgSolutionBackupRestoreSharePointProtectionPolicy | Minor changes |
| Get-MgSolutionBackupRestoreSharePointProtectionPolicySiteInclusionRule | Minor changes |
| Get-MgSolutionBackupRestoreSiteInclusionRule | Minor changes |
| Get-MgSolutionBackupRestoreSiteProtectionUnit | Minor changes |
| Get-MgSubscribedSku | Minor changes |
| Get-MgTeamChannelMember | Minor changes |
| Get-MgTeamChannelRetainedMessage | Minor changes |
| Get-MgTeamIncomingChannel | Minor changes |
| Get-MgTeamOperation | Minor changes |
| Get-MgTeamPermissionGrant | Minor changes |
| Get-MgTeamPermissionGrantCount | Minor changes |
| Get-MgTeamPrimaryChannelMessage | Minor changes |
| Get-MgTeamPrimaryChannelMessageHostedContent | Minor changes |
| Get-MgTeamPrimaryChannelMessageReply | Minor changes |
| Get-MgTeamPrimaryChannelSharedWithTeam | Minor changes |
| Get-MgTeamScheduleOfferShiftRequest | Minor changes |
| Get-MgTeamScheduleOpenShiftChangeRequest | Minor changes |
| Get-MgTeamScheduleShift | Minor changes |
| Get-MgTeamworkDeletedTeam | Minor changes |
| Get-MgTeamworkDeletedTeamChannelRetainedMessage | Minor changes |
| Get-MgTeamworkDeletedTeamChannelSharedWithTeam | Minor changes |
| Get-MgTeamworkDeletedTeamChannelTab | Minor changes |
| Get-MgTenantRelationshipDelegatedAdminCustomer | Minor changes |
| Get-MgTenantRelationshipDelegatedAdminRelationshipOperation | Minor changes |
| Get-MgTenantRelationshipDelegatedAdminRelationshipRequest | Minor changes |
| Get-MgUserActivityHistoryItem | Minor changes |
| Get-MgUserAgreementAcceptance | Minor changes |
| Get-MgUserAuthenticationEmailMethod | Minor changes |
| Get-MgUserAuthenticationFido2Method | Minor changes |
| Get-MgUserAuthenticationFido2MethodCount | Minor changes |
| Get-MgUserAuthenticationMethod | Minor changes |
| Get-MgUserAuthenticationPasswordMethod | Minor changes |
| Get-MgUserAuthenticationPhoneMethod | Minor changes |
| Get-MgUserAuthenticationWindowsHelloForBusinessMethod | Minor changes |
| Get-MgUserCalendarGroup | Minor changes |
| Get-MgUserCalendarPermission | Minor changes |
| Get-MgUserChatInstalledApp | Minor changes |
| Get-MgUserChatMember | Minor changes |
| Get-MgUserChatMessage | Minor changes |
| Get-MgUserChatMessageCount | Minor changes |
| Get-MgUserChatMessageDelta | Minor changes |
| Get-MgUserChatMessageHostedContent | Minor changes |
| Get-MgUserChatMessageHostedContentCount | Minor changes |
| Get-MgUserChatMessageReply | Minor changes |
| Get-MgUserChatMessageReplyDelta | Minor changes |
| Get-MgUserChatPermissionGrant | Minor changes |
| Get-MgUserChatPinnedMessage | Minor changes |
| Get-MgUserChatRetainedMessage | Minor changes |
| Get-MgUserContactDelta | Minor changes |
| Get-MgUserContactFolderChildFolder | Minor changes |
| Get-MgUserContactFolderChildFolderContactDelta | Minor changes |
| Get-MgUserContactFolderChildFolderContactExtension | Minor changes |
| Get-MgUserContactFolderChildFolderDelta | Minor changes |
| Get-MgUserContactFolderContactDelta | Minor changes |
| Get-MgUserContactFolderDelta | Minor changes |
| Get-MgUserCreatedObjectAsServicePrincipal | Minor changes |
| Get-MgUserDriveContentTypeBaseType | Minor changes |
| Get-MgUserDriveFollowing | Minor changes |
| Get-MgUserDriveItemActivityByInterval | Minor changes |
| Get-MgUserDriveItemAnalyticItemActivityStat | Minor changes |
| Get-MgUserDriveItemDelta | Minor changes |
| Get-MgUserDriveItemListItemActivityByInterval | Minor changes |
| Get-MgUserDriveItemPermission | Minor changes |
| Get-MgUserDriveListContentTypeColumnLink | Minor changes |
| Get-MgUserDriveListContentTypeCompatibleHubContentType | Minor changes |
| Get-MgUserDriveListItemActivityByInterval | Minor changes |
| Get-MgUserDriveListItemDelta | Minor changes |
| Get-MgUserDriveListItemDocumentSetVersion | Minor changes |
| Get-MgUserDriveListItemVersion | Minor changes |
| Get-MgUserDriveRootActivityByInterval | Minor changes |
| Get-MgUserDriveRootDelta | Minor changes |
| Get-MgUserDriveRootListItemActivityByInterval | Minor changes |
| Get-MgUserDriveRootPermission | Minor changes |
| Get-MgUserDriveRootSubscription | Minor changes |
| Get-MgUserDriveSpecial | Minor changes |
| Get-MgUserEvent | Minor changes |
| Get-MgUserEventDelta | Minor changes |
| Get-MgUserEventInstance | Minor changes |
| Get-MgUserEventInstanceDelta | Minor changes |
| Get-MgUserEventInstanceExtension | Minor changes |
| Get-MgUserExtension | Minor changes |
| Get-MgUserInsightTrending | Minor changes |
| Get-MgUserLicenseDetail | Minor changes |
| Get-MgUserLicenseDetailCount | Minor changes |
| Get-MgUserLicenseDetailTeamLicensingDetail | Minor changes |
| Get-MgUserMailFolderChildFolderDelta | Minor changes |
| Get-MgUserMailFolderChildFolderMessageDelta | Minor changes |
| Get-MgUserMailFolderDelta | Minor changes |
| Get-MgUserMailFolderMessage | Minor changes |
| Get-MgUserMailFolderMessageDelta | Minor changes |
| Get-MgUserMailFolderMessageExtension | Minor changes |
| Get-MgUserManagedDevice | Minor changes |
| Get-MgUserManagedDeviceCompliancePolicyState | Minor changes |
| Get-MgUserManagedDeviceLogCollectionResponse | Minor changes |
| Get-MgUserManagedDeviceWindowsProtectionStateDetectedMalwareState | Minor changes |
| Get-MgUserMemberOf | Minor changes |
| Get-MgUserMessageDelta | Minor changes |
| Get-MgUserMessageExtension | Minor changes |
| Get-MgUserOnenoteNotebookFromWebUrl | Minor changes |
| Get-MgUserOnenoteNotebookSection | Minor changes |
| Get-MgUserOnenoteNotebookSectionGroup | Minor changes |
| Get-MgUserOnenotePage | Minor changes |
| Get-MgUserOnenoteSectionGroupSection | Minor changes |
| Get-MgUserOnenoteSectionPage | Minor changes |
| Get-MgUserOnlineMeetingAttendanceReport | Minor changes |
| Get-MgUserOnlineMeetingAttendanceReportAttendanceRecord | Minor changes |
| Get-MgUserOnlineMeetingRecording | Minor changes |
| Get-MgUserOnlineMeetingRecordingContent | Minor changes |
| Get-MgUserOnlineMeetingRecordingCount | Minor changes |
| Get-MgUserOnlineMeetingRecordingDelta | Minor changes |
| Get-MgUserOnlineMeetingTranscript | Minor changes |
| Get-MgUserOnlineMeetingTranscriptContent | Minor changes |
| Get-MgUserOnlineMeetingTranscriptCount | Minor changes |
| Get-MgUserOnlineMeetingTranscriptDelta | Minor changes |
| Get-MgUserOnlineMeetingTranscriptMetadataContent | Minor changes |
| Get-MgUserOnlineMeetingVirtualAppointmentJoinWebUrl | Minor changes |
| Get-MgUserOwnedObject | Minor changes |
| Get-MgUserOwnedObjectAsApplication | Minor changes |
| Get-MgUserOwnedObjectAsGroup | Minor changes |
| Get-MgUserRegisteredDeviceAsAppRoleAssignment | Minor changes |
| Get-MgUserRegisteredDeviceAsDevice | Minor changes |
| Get-MgUserRegisteredDeviceAsEndpoint | Minor changes |
| Get-MgUserSettingStorageQuotaService | Minor changes |
| Get-MgUserSettingWindows | Minor changes |
| Get-MgUserTeamworkAssociatedTeam | Minor changes |
| Get-MgUserTodoListDelta | Minor changes |
| Get-MgUserTodoListExtension | Minor changes |
| Get-MgUserTodoTask | Minor changes |
| Get-MgUserTodoTaskChecklistItem | Minor changes |
| Get-MgUserTodoTaskDelta | Minor changes |
| Get-MgUserTransitiveMemberOf | Minor changes |
| Get-MgVirtualEventSessionAttendanceReport | Minor changes |
| Get-MgVirtualEventSessionAttendanceReportAttendanceRecord | Minor changes |
| Get-MgVirtualEventTownhallSession | Minor changes |
| Get-MgVirtualEventWebinarPresenter | Minor changes |
| Get-MgVirtualEventWebinarRegistrationSession | Minor changes |
| Get-MgVirtualEventWebinarSessionAttendanceReport | Minor changes |
| Grant-MgGroupDriveItemPermission | Minor changes |
| Grant-MgGroupDriveRootPermission | Minor changes |
| Grant-MgGroupSitePermission | Minor changes |
| Grant-MgUserDriveItemPermission | Minor changes |
| Grant-MgUserDriveRootPermission | Minor changes |
| Hide-MgUserChatForUser | Minor changes |
| Import-MgDeviceManagementImportedWindowsAutopilotDeviceIdentity | Minor changes |
| Invoke-MgAcceptGroupEvent | Minor changes |
| Invoke-MgAcceptGroupEventTentatively | Minor changes |
| Invoke-MgAcceptUserEvent | Minor changes |
| Invoke-MgAcceptUserEventInstance | Minor changes |
| Invoke-MgAcceptUserEventInstanceTentatively | Minor changes |
| Invoke-MgAcceptUserEventTentatively | Minor changes |
| Invoke-MgBeginDeviceManagementRemoteAssistancePartnerOnboarding | Minor changes |
| Invoke-MgCalendarGroupCalendar | Minor changes |
| Invoke-MgCheckinGroupDriveItem | Minor changes |
| Invoke-MgCheckinGroupDriveRoot | Minor changes |
| Invoke-MgCheckinUserDriveItem | Minor changes |
| Invoke-MgCheckinUserDriveRoot | Minor changes |
| Invoke-MgCheckoutGroupDriveItem | Minor changes |
| Invoke-MgCheckoutGroupDriveRoot | Minor changes |
| Invoke-MgCheckoutUserDriveItem | Minor changes |
| Invoke-MgCheckoutUserDriveRoot | Minor changes |
| Invoke-MgCleanDeviceManagementManagedDeviceWindowsDevice | Minor changes |
| Invoke-MgCleanUserManagedDeviceWindowsDevice | Minor changes |
| Invoke-MgDeactivateSolutionBackupRestoreProtectionPolicy | Minor changes |
| Invoke-MgDeactivateSolutionBackupRestoreServiceApp | Minor changes |
| Invoke-MgDeclineGroupEvent | Minor changes |
| Invoke-MgDeclineUserEvent | Minor changes |
| Invoke-MgDeclineUserEventInstance | Minor changes |
| Invoke-MgDismissGroupEventReminder | Minor changes |
| Invoke-MgDismissUserEventInstanceReminder | Minor changes |
| Invoke-MgDismissUserEventReminder | Minor changes |
| Invoke-MgDownDeviceManagementManagedDeviceShut | Minor changes |
| Invoke-MgDownUserManagedDeviceShut | Minor changes |
| Invoke-MgDownloadDeviceManagementApplePushNotificationCertificateApplePushNotificationCertificateSigningRequest | Minor changes |
| Invoke-MgExtractGroupDriveItemSensitivityLabel | Minor changes |
| Invoke-MgExtractGroupDriveRootSensitivityLabel | Minor changes |
| Invoke-MgExtractUserDriveItemSensitivityLabel | Minor changes |
| Invoke-MgExtractUserDriveRootSensitivityLabel | Minor changes |
| Invoke-MgFollowGroupDriveItem | Minor changes |
| Invoke-MgFollowGroupDriveRoot | Minor changes |
| Invoke-MgFollowUserDriveItem | Minor changes |
| Invoke-MgFollowUserDriveRoot | Minor changes |
| Invoke-MgForwardGroupEvent | Minor changes |
| Invoke-MgForwardUserEvent | Minor changes |
| Invoke-MgForwardUserEventInstance | Minor changes |
| Invoke-MgForwardUserMailFolderChildFolderMessage | Minor changes |
| Invoke-MgForwardUserMailFolderMessage | Minor changes |
| Invoke-MgForwardUserMessage | Minor changes |
| Invoke-MgGraphGroupDrive | Minor changes |
| Invoke-MgGraphUserChat | Minor changes |
| Invoke-MgGraphUserDrive | Minor changes |
| Invoke-MgInviteGroupDriveItem | Minor changes |
| Invoke-MgInviteGroupDriveRoot | Minor changes |
| Invoke-MgInviteUserDriveItem | Minor changes |
| Invoke-MgInviteUserDriveRoot | Minor changes |
| Invoke-MgLogoutDeviceManagementManagedDeviceSharedAppleDeviceActiveUser | Minor changes |
| Invoke-MgLogoutUserManagedDeviceSharedAppleDeviceActiveUser | Minor changes |
| Invoke-MgMarkUserChatReadForUser | Minor changes |
| Invoke-MgMarkUserChatUnreadForUser | Minor changes |
| Invoke-MgPreviewGroupDriveItem | Minor changes |
| Invoke-MgPreviewGroupDriveRoot | Minor changes |
| Invoke-MgPreviewGroupOnenotePage | Minor changes |
| Invoke-MgPreviewSiteOnenoteNotebookSectionGroupSectionPage | Minor changes |
| Invoke-MgPreviewSiteOnenoteNotebookSectionPage | Minor changes |
| Invoke-MgPreviewSiteOnenotePage | Minor changes |
| Invoke-MgPreviewSiteOnenoteSectionGroupSectionPage | Minor changes |
| Invoke-MgPreviewSiteOnenoteSectionPage | Minor changes |
| Invoke-MgPreviewUserDriveItem | Minor changes |
| Invoke-MgPreviewUserDriveRoot | Minor changes |
| Invoke-MgPreviewUserOnenotePage | Minor changes |
| Invoke-MgReauthorizeGroupDriveItemSubscription | Minor changes |
| Invoke-MgReauthorizeGroupDriveListSubscription | Minor changes |
| Invoke-MgReauthorizeGroupDriveRootSubscription | Minor changes |
| Invoke-MgReauthorizeGroupSiteListSubscription | Minor changes |
| Invoke-MgReauthorizeUserDriveItemSubscription | Minor changes |
| Invoke-MgReauthorizeUserDriveListSubscription | Minor changes |
| Invoke-MgReauthorizeUserDriveRootSubscription | Minor changes |
| Invoke-MgRecentGroupDrive | Minor changes |
| Invoke-MgRecentUserActivity | Minor changes |
| Invoke-MgRecentUserDrive | Minor changes |
| Invoke-MgReplyAllUserMailFolderChildFolderMessage | Minor changes |
| Invoke-MgReplyAllUserMailFolderMessage | Minor changes |
| Invoke-MgReplyAllUserMessage | Minor changes |
| Invoke-MgReplyGroupConversationThread | Minor changes |
| Invoke-MgReplyGroupThread | Minor changes |
| Invoke-MgReplyUserMailFolderChildFolderMessage | Minor changes |
| Invoke-MgReplyUserMailFolderMessage | Minor changes |
| Invoke-MgReplyUserMessage | Minor changes |
| Invoke-MgRetireDeviceManagementManagedDevice | Minor changes |
| Invoke-MgRetireUserManagedDevice | Minor changes |
| Invoke-MgScanDeviceManagementManagedDeviceWindowsDefender | Minor changes |
| Invoke-MgScanUserManagedDeviceWindowsDefender | Minor changes |
| Invoke-MgScheduleDeviceManagementDeviceCompliancePolicyActionForRule | Minor changes |
| Invoke-MgSnoozeGroupEventReminder | Minor changes |
| Invoke-MgSnoozeUserEventInstanceReminder | Minor changes |
| Invoke-MgSnoozeUserEventReminder | Minor changes |
| Invoke-MgSoftUserChatMessageDelete | Minor changes |
| Invoke-MgSoftUserChatMessageReplyDelete | Minor changes |
| Invoke-MgSummarizeDeviceManagementUserExperienceAnalyticDevicePerformanceDevice | Minor changes |
| Invoke-MgSupportedUserOutlookLanguage | Minor changes |
| Invoke-MgTerminateDeviceManagementPartner | Minor changes |
| Invoke-MgTimeUserOutlook | Minor changes |
| Invoke-MgTroubleshootDeviceManagementVirtualEndpointCloudPc | Minor changes |
| Invoke-MgUnassignDeviceManagementWindowsAutopilotDeviceIdentityUserFromDevice | Minor changes |
| Invoke-MgUnfollowGroupDriveItem | Minor changes |
| Invoke-MgUnfollowGroupDriveRoot | Minor changes |
| Invoke-MgUnfollowUserDriveItem | Minor changes |
| Invoke-MgUnfollowUserDriveRoot | Minor changes |
| Join-MgGroupDriveListContentTypeWithHubSite | Minor changes |
| Join-MgGroupSiteContentTypeWithHubSite | Minor changes |
| Join-MgGroupSiteListContentTypeWithHubSite | Minor changes |
| Join-MgUserDriveListContentTypeWithHubSite | Minor changes |
| Lock-MgDeviceManagementManagedDeviceRemote | Minor changes |
| Lock-MgUserManagedDeviceRemote | Minor changes |
| Move-MgUserMailFolder | Minor changes |
| Move-MgUserMailFolderChildFolder | Minor changes |
| Move-MgUserMailFolderChildFolderMessage | Minor changes |
| Move-MgUserMailFolderMessage | Minor changes |
| Move-MgUserMessage | Minor changes |
| New-MgChatMessage | Minor changes |
| New-MgChatPinnedMessage | Minor changes |
| New-MgDeviceAppManagementMobileApp | Minor changes |
| New-MgDeviceManagementDeviceConfiguration | Minor changes |
| New-MgDeviceManagementManagedDeviceLogCollectionRequestDownloadUrl | Minor changes |
| New-MgDeviceManagementMobileAppTroubleshootingEventAppLogCollectionRequestDownloadUrl | Minor changes |
| New-MgDeviceManagementRoleDefinition | Minor changes |
| New-MgGroupDriveItemLink | Minor changes |
| New-MgGroupDriveItemListItemLink | Minor changes |
| New-MgGroupDriveItemUploadSession | Minor changes |
| New-MgGroupDriveListItemLink | Minor changes |
| New-MgGroupDriveRootLink | Minor changes |
| New-MgGroupDriveRootListItemLink | Minor changes |
| New-MgGroupDriveRootUploadSession | Minor changes |
| New-MgGroupSiteListItemLink | Minor changes |
| New-MgTeamChannelMessageReply | Minor changes |
| New-MgUser | Minor changes |
| New-MgUserDriveItemLink | Minor changes |
| New-MgUserDriveItemListItemLink | Minor changes |
| New-MgUserDriveItemUploadSession | Minor changes |
| New-MgUserDriveListItemLink | Minor changes |
| New-MgUserDriveRootLink | Minor changes |
| New-MgUserDriveRootListItemLink | Minor changes |
| New-MgUserDriveRootUploadSession | Minor changes |
| New-MgUserEventAttachmentUploadSession | Minor changes |
| New-MgUserEventInstanceAttachmentUploadSession | Minor changes |
| New-MgUserMailFolderChildFolderMessageAttachmentUploadSession | Minor changes |
| New-MgUserMailFolderChildFolderMessageForward | Minor changes |
| New-MgUserMailFolderChildFolderMessageReply | Minor changes |
| New-MgUserMailFolderChildFolderMessageReplyAll | Minor changes |
| New-MgUserMailFolderMessageAttachmentUploadSession | Minor changes |
| New-MgUserMailFolderMessageForward | Minor changes |
| New-MgUserMailFolderMessageReply | Minor changes |
| New-MgUserMailFolderMessageReplyAll | Minor changes |
| New-MgUserMessageAttachmentUploadSession | Minor changes |
| New-MgUserMessageForward | Minor changes |
| New-MgUserMessageReply | Minor changes |
| New-MgUserMessageReplyAll | Minor changes |
| New-MgUserTodoListTaskAttachmentUploadSession | Minor changes |
| Publish-MgGroupDriveListContentType | Minor changes |
| Publish-MgGroupSiteContentType | Minor changes |
| Publish-MgGroupSiteListContentType | Minor changes |
| Publish-MgUserDriveListContentType | Minor changes |
| Remove-MgDeviceAppManagementManagedEBookAssignment | Minor changes |
| Remove-MgDeviceAppManagementMobileApp | Minor changes |
| Remove-MgDeviceManagementDeviceCompliancePolicy | Minor changes |
| Remove-MgDeviceManagementDeviceConfiguration | Minor changes |
| Remove-MgDeviceManagementManagedDeviceUserFromSharedAppleDevice | Minor changes |
| Remove-MgDeviceManagementRoleDefinition | Minor changes |
| Remove-MgGroupDriveItemPermanent | Minor changes |
| Remove-MgGroupDriveRootPermanent | Minor changes |
| Remove-MgGroupSite | Minor changes |
| Remove-MgGroupThread | Minor changes |
| Remove-MgIdentityConditionalAccessNamedLocation | Minor changes |
| Remove-MgIdentityGovernanceLifecycleWorkflowCustomTaskExtension | Minor changes |
| Remove-MgSecurityAttackSimulation | Minor changes |
| Remove-MgTeamScheduleShift | Minor changes |
| Remove-MgUserAuthenticationFido2Method | Minor changes |
| Remove-MgUserDriveItemPermanent | Minor changes |
| Remove-MgUserDriveRootPermanent | Minor changes |
| Remove-MgUserFollowedSite | Minor changes |
| Remove-MgUserManagedDeviceUserFromSharedAppleDevice | Minor changes |
| Rename-MgDeviceManagementVirtualEndpointCloudPc | Minor changes |
| Request-MgDeviceManagementManagedDeviceRemoteAssistance | Minor changes |
| Request-MgUserManagedDeviceRemoteAssistance | Minor changes |
| Reset-MgDeviceManagementManagedDevicePasscode | Minor changes |
| Reset-MgUserAuthenticationMethodPassword | Minor changes |
| Reset-MgUserManagedDevicePasscode | Minor changes |
| Restart-MgDeviceManagementManagedDeviceNow | Minor changes |
| Restart-MgDeviceManagementVirtualEndpointCloudPc | Minor changes |
| Restart-MgUserManagedDeviceNow | Minor changes |
| Restore-MgDeviceManagementManagedDevicePasscode | Minor changes |
| Restore-MgDeviceManagementVirtualEndpointCloudPc | Minor changes |
| Restore-MgGroupDriveItem | Minor changes |
| Restore-MgGroupDriveItemListItemDocumentSetVersion | Minor changes |
| Restore-MgGroupDriveItemListItemVersion | Minor changes |
| Restore-MgGroupDriveItemVersion | Minor changes |
| Restore-MgGroupDriveListItemDocumentSetVersion | Minor changes |
| Restore-MgGroupDriveListItemVersion | Minor changes |
| Restore-MgGroupDriveRoot | Minor changes |
| Restore-MgGroupDriveRootListItemDocumentSetVersion | Minor changes |
| Restore-MgGroupDriveRootListItemVersion | Minor changes |
| Restore-MgGroupDriveRootVersion | Minor changes |
| Restore-MgGroupSiteListItemDocumentSetVersion | Minor changes |
| Restore-MgGroupSiteListItemVersion | Minor changes |
| Restore-MgUserDriveItem | Minor changes |
| Restore-MgUserDriveItemListItemDocumentSetVersion | Minor changes |
| Restore-MgUserDriveItemListItemVersion | Minor changes |
| Restore-MgUserDriveItemVersion | Minor changes |
| Restore-MgUserDriveListItemDocumentSetVersion | Minor changes |
| Restore-MgUserDriveListItemVersion | Minor changes |
| Restore-MgUserDriveRoot | Minor changes |
| Restore-MgUserDriveRootListItemDocumentSetVersion | Minor changes |
| Restore-MgUserDriveRootListItemVersion | Minor changes |
| Restore-MgUserDriveRootVersion | Minor changes |
| Restore-MgUserManagedDevicePasscode | Minor changes |
| Search-MgGroupDrive | Minor changes |
| Search-MgGroupDriveItem | Minor changes |
| Search-MgGroupDriveRoot | Minor changes |
| Search-MgUserDrive | Minor changes |
| Search-MgUserDriveItem | Minor changes |
| Search-MgUserDriveRoot | Minor changes |
| Send-MgDeviceManagementNotificationMessageTemplateTestMessage | Minor changes |
| Send-MgUserChatActivityNotification | Minor changes |
| Send-MgUserMailFolderChildFolderMessage | Minor changes |
| Send-MgUserMailFolderMessage | Minor changes |
| Send-MgUserMessage | Minor changes |
| Send-MgUserOnlineMeetingVirtualAppointmentReminderSm | Minor changes |
| Send-MgUserOnlineMeetingVirtualAppointmentSm | Minor changes |
| Send-MgUserTeamworkActivityNotification | Minor changes |
| Set-MgDeviceManagementDeviceCompliancePolicy | Minor changes |
| Set-MgDeviceManagementDeviceConfiguration | Minor changes |
| Set-MgDeviceManagementDeviceEnrollmentConfiguration | Minor changes |
| Set-MgDeviceManagementDeviceEnrollmentConfigurationPriority | Minor changes |
| Set-MgDeviceManagementVirtualEndpointProvisioningPolicy | Minor changes |
| Set-MgDeviceManagementVirtualEndpointUserSetting | Minor changes |
| Set-MgDeviceManagementWindowsAutopilotDeviceIdentityUserToDevice | Minor changes |
| Set-MgGroupDriveItemSensitivityLabel | Minor changes |
| Set-MgGroupDriveRootSensitivityLabel | Minor changes |
| Set-MgUserChatMessageReaction | Minor changes |
| Set-MgUserChatMessageReplyReaction | Minor changes |
| Set-MgUserDriveItemSensitivityLabel | Minor changes |
| Set-MgUserDriveRootSensitivityLabel | Minor changes |
| Set-MgUserPresence | Minor changes |
| Set-MgUserPresenceStatusMessage | Minor changes |
| Set-MgUserPresenceUserPreferredPresence | Minor changes |
| Skip-MgDeviceManagementManagedDeviceActivationLock | Minor changes |
| Skip-MgUserManagedDeviceActivationLock | Minor changes |
| Start-MgDeviceManagementVirtualEndpointOnPremiseConnectionHealthCheck | Minor changes |
| Stop-MgDeviceManagementVirtualEndpointCloudPcGracePeriod | Minor changes |
| Stop-MgGroupEvent | Minor changes |
| Stop-MgUserEvent | Minor changes |
| Stop-MgUserEventInstance | Minor changes |
| Sync-MgDeviceManagementExchangeConnector | Minor changes |
| Sync-MgDeviceManagementManagedDevice | Minor changes |
| Sync-MgUserManagedDevice | Minor changes |
| Test-MgGroupDriveItemPermission | Minor changes |
| Test-MgGroupDriveListContentTypePublished | Minor changes |
| Test-MgGroupDriveRootPermission | Minor changes |
| Test-MgGroupSiteContentTypePublished | Minor changes |
| Test-MgGroupSiteListContentTypePublished | Minor changes |
| Test-MgUserDriveItemPermission | Minor changes |
| Test-MgUserDriveListContentTypePublished | Minor changes |
| Test-MgUserDriveRootPermission | Minor changes |
| Undo-MgUserChatMessageReplySoftDelete | Minor changes |
| Undo-MgUserChatMessageSoftDelete | Minor changes |
| Unpublish-MgGroupDriveListContentType | Minor changes |
| Unpublish-MgGroupSiteContentType | Minor changes |
| Unpublish-MgGroupSiteListContentType | Minor changes |
| Unpublish-MgUserDriveListContentType | Minor changes |
| Update-MgDeviceAppManagement | Minor changes |
| Update-MgDeviceAppManagementManagedEBookAssignment | Minor changes |
| Update-MgDeviceAppManagementMobileApp | Minor changes |
| Update-MgDeviceManagement | Minor changes |
| Update-MgDeviceManagementDeviceConfiguration | Minor changes |
| Update-MgDeviceManagementManagedDeviceWindowsDeviceAccount | Minor changes |
| Update-MgDeviceManagementRoleDefinition | Minor changes |
| Update-MgDeviceManagementWindowsAutopilotDeviceIdentityDeviceProperty | Minor changes |
| Update-MgSecurityCaseEdiscoveryCaseReviewSet | Minor changes |
| Update-MgTeamChannelMember | Minor changes |
| Update-MgUserChatInstalledApp | Minor changes |
| Update-MgUserManagedDeviceWindowsDeviceAccount | Minor changes |

# Cmdlet beta Changes

## Statistics
- **Total cmdlets**: 15121
- **Total cmdlet changes**: 2533
- **Added**: 737
- **Removed**: 0
- **Modified**: 1796

### Added Cmdlets (737)

| Command |
|---------|
| Add-MgBetaGroupTeamChannelAllMember |
| Add-MgBetaGroupTeamChannelMember |
| Add-MgBetaGroupTeamMember |
| Add-MgBetaGroupTeamPrimaryChannelAllMember |
| Add-MgBetaGroupTeamPrimaryChannelMember |
| Add-MgBetaTeamChannelAllMember |
| Add-MgBetaTeamPrimaryChannelAllMember |
| Add-MgBetaTeamworkDeletedTeamChannelAllMember |
| Clear-MgBetaGroupTeamChannelMessageReaction |
| Clear-MgBetaGroupTeamChannelMessageReplyReaction |
| Clear-MgBetaGroupTeamPrimaryChannelMessageReaction |
| Clear-MgBetaGroupTeamPrimaryChannelMessageReplyReaction |
| Complete-MgBetaGroupTeamChannelMigration |
| Complete-MgBetaGroupTeamMigration |
| Complete-MgBetaGroupTeamPrimaryChannelMigration |
| Confirm-MgBetaGroupTeamScheduleTimeCard |
| Copy-MgBetaGroupOnenoteNotebookSectionGroupSectionPageToSection |
| Copy-MgBetaGroupOnenoteNotebookSectionGroupSectionToNotebook |
| Copy-MgBetaGroupOnenoteNotebookSectionGroupSectionToSectionGroup |
| Copy-MgBetaGroupOnenoteNotebookSectionPageToSection |
| Copy-MgBetaGroupOnenoteNotebookSectionToNotebook |
| Copy-MgBetaGroupOnenoteNotebookSectionToSectionGroup |
| Copy-MgBetaGroupOnenoteSectionGroupSectionPageToSection |
| Copy-MgBetaGroupOnenoteSectionGroupSectionToNotebook |
| Copy-MgBetaGroupOnenoteSectionGroupSectionToSectionGroup |
| Copy-MgBetaGroupOnenoteSectionPageToSection |
| Copy-MgBetaGroupSiteOnenoteNotebook |
| Copy-MgBetaGroupSiteOnenoteNotebookSectionGroupSectionPageToSection |
| Copy-MgBetaGroupSiteOnenoteNotebookSectionGroupSectionToNotebook |
| Copy-MgBetaGroupSiteOnenoteNotebookSectionGroupSectionToSectionGroup |
| Copy-MgBetaGroupSiteOnenoteNotebookSectionPageToSection |
| Copy-MgBetaGroupSiteOnenoteNotebookSectionToNotebook |
| Copy-MgBetaGroupSiteOnenoteNotebookSectionToSectionGroup |
| Copy-MgBetaGroupSiteOnenotePageToSection |
| Copy-MgBetaGroupSiteOnenoteSectionGroupSectionPageToSection |
| Copy-MgBetaGroupSiteOnenoteSectionGroupSectionToNotebook |
| Copy-MgBetaGroupSiteOnenoteSectionGroupSectionToSectionGroup |
| Copy-MgBetaGroupSiteOnenoteSectionPageToSection |
| Copy-MgBetaGroupSiteOnenoteSectionToNotebook |
| Copy-MgBetaGroupSiteOnenoteSectionToSectionGroup |
| Copy-MgBetaGroupTeam |
| Copy-MgBetaUserOnenoteNotebookSectionGroupSectionPageToSection |
| Copy-MgBetaUserOnenoteNotebookSectionGroupSectionToNotebook |
| Copy-MgBetaUserOnenoteNotebookSectionGroupSectionToSectionGroup |
| Copy-MgBetaUserOnenoteNotebookSectionPageToSection |
| Copy-MgBetaUserOnenoteNotebookSectionToNotebook |
| Copy-MgBetaUserOnenoteNotebookSectionToSectionGroup |
| Copy-MgBetaUserOnenoteSectionGroupSectionPageToSection |
| Copy-MgBetaUserOnenoteSectionGroupSectionToNotebook |
| Copy-MgBetaUserOnenoteSectionGroupSectionToSectionGroup |
| Copy-MgBetaUserOnenoteSectionPageToSection |
| Disable-MgBetaMeAuthenticationMethodSmsSignIn |
| Enable-MgBetaMeAuthenticationMethodSmsSignIn |
| Enable-MgBetaSolutionBackupRestore |
| Find-MgBetaTenantRelationshipTenantInformationByDomainName |
| Find-MgBetaTenantRelationshipTenantInformationByTenantId |
| Get-MgBetaAdministrativeUnitDeletedMember |
| Get-MgBetaAdministrativeUnitDeletedMemberCount |
| Get-MgBetaAuditLogSignUp |
| Get-MgBetaAuditLogSignUpCount |
| Get-MgBetaCommunicationCallContentSharingSessionPngOfCurrentSlide |
| Get-MgBetaDeviceManagementReportDeviceAppInstallationStatusReport |
| Get-MgBetaDeviceManagementReportSecurityTaskAppReport |
| Get-MgBetaDeviceManagementUserRoleDetail |
| Get-MgBetaDeviceRegisteredOwnerAsAppRoleAssignment |
| Get-MgBetaDeviceRegisteredOwnerCountAsAppRoleAssignment |
| Get-MgBetaDeviceRegisteredUserAsAppRoleAssignment |
| Get-MgBetaDeviceRegisteredUserCountAsAppRoleAssignment |
| Get-MgBetaDeviceTemplate |
| Get-MgBetaDeviceTemplateCount |
| Get-MgBetaDirectoryAdministrativeUnitDeletedMember |
| Get-MgBetaDirectoryAdministrativeUnitDeletedMemberCount |
| Get-MgBetaDirectoryAuthenticationMethodDevice |
| Get-MgBetaDirectoryAuthenticationMethodDeviceHardwareOathDevice |
| Get-MgBetaDirectoryAuthenticationMethodDeviceHardwareOathDeviceAssignTo |
| Get-MgBetaDirectoryAuthenticationMethodDeviceHardwareOathDeviceAssignToMailboxSetting |
| Get-MgBetaDirectoryAuthenticationMethodDeviceHardwareOathDeviceAssignToServiceProvisioningError |
| Get-MgBetaDirectoryAuthenticationMethodDeviceHardwareOathDeviceAssignToServiceProvisioningErrorCount |
| Get-MgBetaDirectoryAuthenticationMethodDeviceHardwareOathDeviceCount |
| Get-MgBetaDirectoryCertificateAuthorityMutualTlOauthConfiguration |
| Get-MgBetaDirectoryCertificateAuthorityMutualTlOauthConfigurationCount |
| Get-MgBetaDirectoryPublicKeyInfrastructure |
| Get-MgBetaDirectoryPublicKeyInfrastructureCertificateBasedAuthConfiguration |
| Get-MgBetaDirectoryPublicKeyInfrastructureCertificateBasedAuthConfigurationCertificateAuthority |
| Get-MgBetaDirectoryPublicKeyInfrastructureCertificateBasedAuthConfigurationCertificateAuthorityCount |
| Get-MgBetaDirectoryPublicKeyInfrastructureCertificateBasedAuthConfigurationCount |
| Get-MgBetaDirectoryTemplate |
| Get-MgBetaDirectoryTemplateDeviceInstance |
| Get-MgBetaDirectoryTemplateDeviceInstanceByDeviceId |
| Get-MgBetaDirectoryTemplateDeviceInstanceCount |
| Get-MgBetaDirectoryTemplateDeviceTemplate |
| Get-MgBetaDirectoryTemplateDeviceTemplateCount |
| Get-MgBetaDirectoryTemplateDeviceTemplateOwner |
| Get-MgBetaDirectoryTemplateDeviceTemplateOwnerCount |
| Get-MgBetaEducationReport |
| Get-MgBetaEducationReportReadingAssignmentSubmission |
| Get-MgBetaEducationReportReadingAssignmentSubmissionCount |
| Get-MgBetaEducationReportReflectCheck |
| Get-MgBetaEducationReportReflectCheckInResponseCount |
| Get-MgBetaGroupEventExceptionOccurrenceDelta |
| Get-MgBetaGroupEventExceptionOccurrenceInstanceDelta |
| Get-MgBetaGroupEventInstanceDelta |
| Get-MgBetaGroupEventInstanceExceptionOccurrenceDelta |
| Get-MgBetaGroupOnenote |
| Get-MgBetaGroupOnenoteNotebookRecentNotebook |
| Get-MgBetaGroupOnenoteNotebookSectionCount |
| Get-MgBetaGroupOnenoteNotebookSectionGroupCount |
| Get-MgBetaGroupOnenoteNotebookSectionGroupParentNotebook |
| Get-MgBetaGroupOnenoteNotebookSectionGroupParentSectionGroup |
| Get-MgBetaGroupOnenoteNotebookSectionGroupSection |
| Get-MgBetaGroupOnenoteNotebookSectionGroupSectionCount |
| Get-MgBetaGroupOnenoteNotebookSectionGroupSectionPage |
| Get-MgBetaGroupOnenoteNotebookSectionGroupSectionPageContent |
| Get-MgBetaGroupOnenoteNotebookSectionGroupSectionPageCount |
| Get-MgBetaGroupOnenoteNotebookSectionGroupSectionPageParentNotebook |
| Get-MgBetaGroupOnenoteNotebookSectionGroupSectionPageParentSection |
| Get-MgBetaGroupOnenoteNotebookSectionGroupSectionParentNotebook |
| Get-MgBetaGroupOnenoteNotebookSectionGroupSectionParentSectionGroup |
| Get-MgBetaGroupOnenoteNotebookSectionPage |
| Get-MgBetaGroupOnenoteNotebookSectionPageContent |
| Get-MgBetaGroupOnenoteNotebookSectionPageCount |
| Get-MgBetaGroupOnenoteNotebookSectionPageParentNotebook |
| Get-MgBetaGroupOnenoteNotebookSectionPageParentSection |
| Get-MgBetaGroupOnenoteNotebookSectionParentNotebook |
| Get-MgBetaGroupOnenoteNotebookSectionParentSectionGroup |
| Get-MgBetaGroupOnenotePageParentNotebook |
| Get-MgBetaGroupOnenotePageParentSection |
| Get-MgBetaGroupOnenoteSectionGroupParentNotebook |
| Get-MgBetaGroupOnenoteSectionGroupParentSectionGroup |
| Get-MgBetaGroupOnenoteSectionGroupSectionCount |
| Get-MgBetaGroupOnenoteSectionGroupSectionPage |
| Get-MgBetaGroupOnenoteSectionGroupSectionPageContent |
| Get-MgBetaGroupOnenoteSectionGroupSectionPageCount |
| Get-MgBetaGroupOnenoteSectionGroupSectionPageParentNotebook |
| Get-MgBetaGroupOnenoteSectionGroupSectionPageParentSection |
| Get-MgBetaGroupOnenoteSectionGroupSectionParentNotebook |
| Get-MgBetaGroupOnenoteSectionGroupSectionParentSectionGroup |
| Get-MgBetaGroupOnenoteSectionPageContent |
| Get-MgBetaGroupOnenoteSectionPageCount |
| Get-MgBetaGroupOnenoteSectionPageParentNotebook |
| Get-MgBetaGroupOnenoteSectionPageParentSection |
| Get-MgBetaGroupOnenoteSectionParentNotebook |
| Get-MgBetaGroupOnenoteSectionParentSectionGroup |
| Get-MgBetaGroupSiteOnenoteNotebookFromWebUrl |
| Get-MgBetaGroupSiteOnenoteNotebookRecentNotebook |
| Get-MgBetaGroupTeamChannelAllMemberCount |
| Get-MgBetaGroupTeamChannelMessageDelta |
| Get-MgBetaGroupTeamChannelMessageReplyDelta |
| Get-MgBetaGroupTeamChannelRetainedMessage |
| Get-MgBetaGroupTeamOwnerByUserPrincipalName |
| Get-MgBetaGroupTeamPrimaryChannelAllMemberCount |
| Get-MgBetaGroupTeamPrimaryChannelMessageDelta |
| Get-MgBetaGroupTeamPrimaryChannelMessageReplyDelta |
| Get-MgBetaIdentityProductChange |
| Get-MgBetaIdentityProductChangeCount |
| Get-MgBetaMeAuthentication |
| Get-MgBetaMeAuthenticationEmailMethod |
| Get-MgBetaMeAuthenticationEmailMethodCount |
| Get-MgBetaMeAuthenticationFido2Method |
| Get-MgBetaMeAuthenticationFido2MethodCount |
| Get-MgBetaMeAuthenticationHardwareOathMethod |
| Get-MgBetaMeAuthenticationHardwareOathMethodCount |
| Get-MgBetaMeAuthenticationHardwareOathMethodDevice |
| Get-MgBetaMeAuthenticationHardwareOathMethodDeviceAssignTo |
| Get-MgBetaMeAuthenticationHardwareOathMethodDeviceAssignToMailboxSetting |
| Get-MgBetaMeAuthenticationHardwareOathMethodDeviceAssignToServiceProvisioningError |
| Get-MgBetaMeAuthenticationHardwareOathMethodDeviceAssignToServiceProvisioningErrorCount |
| Get-MgBetaMeAuthenticationHardwareOathMethodDeviceHardwareOathDevice |
| Get-MgBetaMeAuthenticationHardwareOathMethodDeviceHardwareOathDeviceAssignTo |
| Get-MgBetaMeAuthenticationHardwareOathMethodDeviceHardwareOathDeviceAssignToMailboxSetting |
| Get-MgBetaMeAuthenticationHardwareOathMethodDeviceHardwareOathDeviceAssignToServiceProvisioningError |
| Get-MgBetaMeAuthenticationHardwareOathMethodDeviceHardwareOathDeviceAssignToServiceProvisioningErrorCount |
| Get-MgBetaMeAuthenticationHardwareOathMethodDeviceHardwareOathDeviceCount |
| Get-MgBetaMeAuthenticationMethod |
| Get-MgBetaMeAuthenticationMethodCount |
| Get-MgBetaMeAuthenticationMicrosoftAuthenticatorMethod |
| Get-MgBetaMeAuthenticationMicrosoftAuthenticatorMethodCount |
| Get-MgBetaMeAuthenticationMicrosoftAuthenticatorMethodDevice |
| Get-MgBetaMeAuthenticationOperation |
| Get-MgBetaMeAuthenticationOperationCount |
| Get-MgBetaMeAuthenticationPasswordMethod |
| Get-MgBetaMeAuthenticationPasswordMethodCount |
| Get-MgBetaMeAuthenticationPasswordlessMicrosoftAuthenticatorMethod |
| Get-MgBetaMeAuthenticationPasswordlessMicrosoftAuthenticatorMethodCount |
| Get-MgBetaMeAuthenticationPasswordlessMicrosoftAuthenticatorMethodDevice |
| Get-MgBetaMeAuthenticationPhoneMethod |
| Get-MgBetaMeAuthenticationPhoneMethodCount |
| Get-MgBetaMeAuthenticationPlatformCredentialMethod |
| Get-MgBetaMeAuthenticationPlatformCredentialMethodCount |
| Get-MgBetaMeAuthenticationPlatformCredentialMethodDevice |
| Get-MgBetaMeAuthenticationRequirement |
| Get-MgBetaMeAuthenticationSignInPreference |
| Get-MgBetaMeAuthenticationSoftwareOathMethod |
| Get-MgBetaMeAuthenticationSoftwareOathMethodCount |
| Get-MgBetaMeAuthenticationTemporaryAccessPassMethod |
| Get-MgBetaMeAuthenticationTemporaryAccessPassMethodCount |
| Get-MgBetaMeAuthenticationWindowsHelloForBusinessMethod |
| Get-MgBetaMeAuthenticationWindowsHelloForBusinessMethodCount |
| Get-MgBetaMeAuthenticationWindowsHelloForBusinessMethodDevice |
| Get-MgBetaNetworkAccessAlertSummary |
| Get-MgBetaPrivacySubjectRightsRequestApproverByUserPrincipalName |
| Get-MgBetaPrivacySubjectRightsRequestCollaboratorByUserPrincipalName |
| Get-MgBetaPrivacySubjectRightsRequestFinalAttachment |
| Get-MgBetaPrivacySubjectRightsRequestFinalReport |
| Get-MgBetaReportHealthMonitoring |
| Get-MgBetaReportHealthMonitoringAlert |
| Get-MgBetaReportHealthMonitoringAlertConfiguration |
| Get-MgBetaReportHealthMonitoringAlertConfigurationCount |
| Get-MgBetaReportHealthMonitoringAlertCount |
| Get-MgBetaReportServiceActivityActiveUserMetricForDesktopMailByReadEmail |
| Get-MgBetaReportServiceActivityActiveUserMetricForEmailByModernAuthentication |
| Get-MgBetaReportServiceActivityActiveUserMetricForExcelWeb |
| Get-MgBetaReportServiceActivityActiveUserMetricForOneNoteWeb |
| Get-MgBetaReportServiceActivityActiveUserMetricForOutlookMacByReadEmail |
| Get-MgBetaReportServiceActivityActiveUserMetricForOutlookMobileByReadEmail |
| Get-MgBetaReportServiceActivityActiveUserMetricForOutlookWebByAppOpening |
| Get-MgBetaReportServiceActivityActiveUserMetricForOutlookWebByReadEmail |
| Get-MgBetaReportServiceActivityActiveUserMetricForPowerPointWeb |
| Get-MgBetaReportServiceActivityActiveUserMetricForVisioWeb |
| Get-MgBetaReportServiceActivityActiveUserMetricForWordWeb |
| Get-MgBetaReportServiceActivityActiveUserMetricForiOsorAndroidMailByReadEmail |
| Get-MgBetaReportServiceActivityAudioStreamOverUdpMetricForTeam |
| Get-MgBetaReportServiceActivityAudioStreamQoEMetricForTeam |
| Get-MgBetaReportServiceActivityConnectivityMetricForExchange |
| Get-MgBetaReportServiceActivityMessageVolumeMetricForEmailDelivery |
| Get-MgBetaReportServiceActivityMessageVolumeMetricForTeamChat |
| Get-MgBetaReportServiceActivityUsageMetricForTeamByLaunch |
| Get-MgBetaReportServiceActivityUsageMetricForTeamByMeetingJoined |
| Get-MgBetaReportUserInsightDailyMfaTelecomFraud |
| Get-MgBetaReportUserInsightDailyMfaTelecomFraudCount |
| Get-MgBetaReportUserInsightMonthlyMfaRegisteredUser |
| Get-MgBetaReportUserInsightMonthlyMfaRegisteredUserCount |
| Get-MgBetaSecurityAuditLog |
| Get-MgBetaSecurityAuditLogQuery |
| Get-MgBetaSecurityAuditLogQueryCount |
| Get-MgBetaSecurityAuditLogQueryRecord |
| Get-MgBetaSecurityAuditLogQueryRecordCount |
| Get-MgBetaSecurityDataDiscovery |
| Get-MgBetaSecurityDataDiscoveryCloudAppDiscovery |
| Get-MgBetaSecurityDataDiscoveryCloudAppDiscoveryUploadedStream |
| Get-MgBetaSecurityDataDiscoveryCloudAppDiscoveryUploadedStreamCount |
| Get-MgBetaSecuritySubjectRightsRequestApproverByUserPrincipalName |
| Get-MgBetaSecuritySubjectRightsRequestCollaboratorByUserPrincipalName |
| Get-MgBetaSiteOnenote |
| Get-MgBetaSiteOnenoteNotebookRecentNotebook |
| Get-MgBetaSiteOnenoteNotebookSectionCount |
| Get-MgBetaSiteOnenoteNotebookSectionGroupCount |
| Get-MgBetaSiteOnenoteNotebookSectionGroupParentNotebook |
| Get-MgBetaSiteOnenoteNotebookSectionGroupParentSectionGroup |
| Get-MgBetaSiteOnenoteNotebookSectionGroupSection |
| Get-MgBetaSiteOnenoteNotebookSectionGroupSectionCount |
| Get-MgBetaSiteOnenoteNotebookSectionGroupSectionPage |
| Get-MgBetaSiteOnenoteNotebookSectionGroupSectionPageContent |
| Get-MgBetaSiteOnenoteNotebookSectionGroupSectionPageCount |
| Get-MgBetaSiteOnenoteNotebookSectionGroupSectionPageParentNotebook |
| Get-MgBetaSiteOnenoteNotebookSectionGroupSectionPageParentSection |
| Get-MgBetaSiteOnenoteNotebookSectionGroupSectionParentNotebook |
| Get-MgBetaSiteOnenoteNotebookSectionGroupSectionParentSectionGroup |
| Get-MgBetaSiteOnenoteNotebookSectionPage |
| Get-MgBetaSiteOnenoteNotebookSectionPageContent |
| Get-MgBetaSiteOnenoteNotebookSectionPageCount |
| Get-MgBetaSiteOnenoteNotebookSectionPageParentNotebook |
| Get-MgBetaSiteOnenoteNotebookSectionPageParentSection |
| Get-MgBetaSiteOnenoteNotebookSectionParentNotebook |
| Get-MgBetaSiteOnenoteNotebookSectionParentSectionGroup |
| Get-MgBetaSiteOnenotePageParentNotebook |
| Get-MgBetaSiteOnenotePageParentSection |
| Get-MgBetaSiteOnenoteSectionGroupParentNotebook |
| Get-MgBetaSiteOnenoteSectionGroupParentSectionGroup |
| Get-MgBetaSiteOnenoteSectionGroupSectionCount |
| Get-MgBetaSiteOnenoteSectionGroupSectionPage |
| Get-MgBetaSiteOnenoteSectionGroupSectionPageContent |
| Get-MgBetaSiteOnenoteSectionGroupSectionPageCount |
| Get-MgBetaSiteOnenoteSectionGroupSectionPageParentNotebook |
| Get-MgBetaSiteOnenoteSectionGroupSectionPageParentSection |
| Get-MgBetaSiteOnenoteSectionGroupSectionParentNotebook |
| Get-MgBetaSiteOnenoteSectionGroupSectionParentSectionGroup |
| Get-MgBetaSiteOnenoteSectionPageContent |
| Get-MgBetaSiteOnenoteSectionPageCount |
| Get-MgBetaSiteOnenoteSectionPageParentNotebook |
| Get-MgBetaSiteOnenoteSectionPageParentSection |
| Get-MgBetaSiteOnenoteSectionParentNotebook |
| Get-MgBetaSiteOnenoteSectionParentSectionGroup |
| Get-MgBetaSolutionBackupRestoreDriveProtectionUnitBulkAdditionJob |
| Get-MgBetaSolutionBackupRestoreDriveProtectionUnitBulkAdditionJobCount |
| Get-MgBetaSolutionBackupRestoreExchangeProtectionPolicyMailboxProtectionUnitBulkAdditionJob |
| Get-MgBetaSolutionBackupRestoreExchangeProtectionPolicyMailboxProtectionUnitBulkAdditionJobCount |
| Get-MgBetaSolutionBackupRestoreExchangeRestoreSessionMailboxRestoreArtifactBulkAdditionRequest |
| Get-MgBetaSolutionBackupRestoreExchangeRestoreSessionMailboxRestoreArtifactBulkAdditionRequestCount |
| Get-MgBetaSolutionBackupRestoreMailboxProtectionUnitBulkAdditionJob |
| Get-MgBetaSolutionBackupRestoreMailboxProtectionUnitBulkAdditionJobCount |
| Get-MgBetaSolutionBackupRestoreOneDriveForBusinessProtectionPolicyDriveProtectionUnitBulkAdditionJob |
| Get-MgBetaSolutionBackupRestoreOneDriveForBusinessProtectionPolicyDriveProtectionUnitBulkAdditionJobCount |
| Get-MgBetaSolutionBackupRestoreOneDriveForBusinessRestoreSessionDriveRestoreArtifactBulkAdditionRequest |
| Get-MgBetaSolutionBackupRestoreOneDriveForBusinessRestoreSessionDriveRestoreArtifactBulkAdditionRequestCount |
| Get-MgBetaSolutionBackupRestoreSharePointProtectionPolicySiteProtectionUnitBulkAdditionJob |
| Get-MgBetaSolutionBackupRestoreSharePointProtectionPolicySiteProtectionUnitBulkAdditionJobCount |
| Get-MgBetaSolutionBackupRestoreSharePointRestoreSessionSiteRestoreArtifactBulkAdditionRequest |
| Get-MgBetaSolutionBackupRestoreSharePointRestoreSessionSiteRestoreArtifactBulkAdditionRequestCount |
| Get-MgBetaSolutionBackupRestoreSiteProtectionUnitBulkAdditionJob |
| Get-MgBetaSolutionBackupRestoreSiteProtectionUnitBulkAdditionJobCount |
| Get-MgBetaSolutionBusinessScenarioPlannerPlan |
| Get-MgBetaTeamChannelAllMemberCount |
| Get-MgBetaTeamOwnerByUserPrincipalName |
| Get-MgBetaTeamPrimaryChannelAllMemberCount |
| Get-MgBetaTeamworkDeletedTeamChannelAllMemberCount |
| Get-MgBetaUserAuthenticationHardwareOathMethod |
| Get-MgBetaUserAuthenticationHardwareOathMethodCount |
| Get-MgBetaUserAuthenticationHardwareOathMethodDevice |
| Get-MgBetaUserAuthenticationHardwareOathMethodDeviceAssignTo |
| Get-MgBetaUserAuthenticationHardwareOathMethodDeviceAssignToMailboxSetting |
| Get-MgBetaUserAuthenticationHardwareOathMethodDeviceAssignToServiceProvisioningError |
| Get-MgBetaUserAuthenticationHardwareOathMethodDeviceAssignToServiceProvisioningErrorCount |
| Get-MgBetaUserAuthenticationHardwareOathMethodDeviceHardwareOathDevice |
| Get-MgBetaUserAuthenticationHardwareOathMethodDeviceHardwareOathDeviceAssignTo |
| Get-MgBetaUserAuthenticationHardwareOathMethodDeviceHardwareOathDeviceAssignToMailboxSetting |
| Get-MgBetaUserAuthenticationHardwareOathMethodDeviceHardwareOathDeviceAssignToServiceProvisioningError |
| Get-MgBetaUserAuthenticationHardwareOathMethodDeviceHardwareOathDeviceAssignToServiceProvisioningErrorCount |
| Get-MgBetaUserAuthenticationHardwareOathMethodDeviceHardwareOathDeviceCount |
| Get-MgBetaUserAuthenticationRequirement |
| Get-MgBetaUserByUserPrincipalName |
| Get-MgBetaUserDeviceTemplate |
| Get-MgBetaUserDeviceTemplateCount |
| Get-MgBetaUserEventExceptionOccurrenceDelta |
| Get-MgBetaUserEventExceptionOccurrenceInstanceDelta |
| Get-MgBetaUserEventInstanceExceptionOccurrenceDelta |
| Get-MgBetaUserMailFolderChildFolderOperation |
| Get-MgBetaUserMailFolderChildFolderOperationCount |
| Get-MgBetaUserMailFolderOperation |
| Get-MgBetaUserMailFolderOperationCount |
| Get-MgBetaUserManagedDeviceCategoryByRef |
| Get-MgBetaUserManagedDevicePowerliftAppDiagnosticDetail |
| Get-MgBetaUserManagedDeviceWithAppInstallationIssue |
| Get-MgBetaUserOnenote |
| Get-MgBetaUserOnenoteNotebookRecentNotebook |
| Get-MgBetaUserOnenoteNotebookSectionCount |
| Get-MgBetaUserOnenoteNotebookSectionGroupCount |
| Get-MgBetaUserOnenoteNotebookSectionGroupParentNotebook |
| Get-MgBetaUserOnenoteNotebookSectionGroupParentSectionGroup |
| Get-MgBetaUserOnenoteNotebookSectionGroupSection |
| Get-MgBetaUserOnenoteNotebookSectionGroupSectionCount |
| Get-MgBetaUserOnenoteNotebookSectionGroupSectionPage |
| Get-MgBetaUserOnenoteNotebookSectionGroupSectionPageContent |
| Get-MgBetaUserOnenoteNotebookSectionGroupSectionPageCount |
| Get-MgBetaUserOnenoteNotebookSectionGroupSectionPageParentNotebook |
| Get-MgBetaUserOnenoteNotebookSectionGroupSectionPageParentSection |
| Get-MgBetaUserOnenoteNotebookSectionGroupSectionParentNotebook |
| Get-MgBetaUserOnenoteNotebookSectionGroupSectionParentSectionGroup |
| Get-MgBetaUserOnenoteNotebookSectionPage |
| Get-MgBetaUserOnenoteNotebookSectionPageContent |
| Get-MgBetaUserOnenoteNotebookSectionPageCount |
| Get-MgBetaUserOnenoteNotebookSectionPageParentNotebook |
| Get-MgBetaUserOnenoteNotebookSectionPageParentSection |
| Get-MgBetaUserOnenoteNotebookSectionParentNotebook |
| Get-MgBetaUserOnenoteNotebookSectionParentSectionGroup |
| Get-MgBetaUserOnenotePageParentNotebook |
| Get-MgBetaUserOnenotePageParentSection |
| Get-MgBetaUserOnenoteSectionGroupParentNotebook |
| Get-MgBetaUserOnenoteSectionGroupParentSectionGroup |
| Get-MgBetaUserOnenoteSectionGroupSectionCount |
| Get-MgBetaUserOnenoteSectionGroupSectionPage |
| Get-MgBetaUserOnenoteSectionGroupSectionPageContent |
| Get-MgBetaUserOnenoteSectionGroupSectionPageCount |
| Get-MgBetaUserOnenoteSectionGroupSectionPageParentNotebook |
| Get-MgBetaUserOnenoteSectionGroupSectionPageParentSection |
| Get-MgBetaUserOnenoteSectionGroupSectionParentNotebook |
| Get-MgBetaUserOnenoteSectionGroupSectionParentSectionGroup |
| Get-MgBetaUserOnenoteSectionPageContent |
| Get-MgBetaUserOnenoteSectionPageCount |
| Get-MgBetaUserOnenoteSectionPageParentNotebook |
| Get-MgBetaUserOnenoteSectionPageParentSection |
| Get-MgBetaUserOnenoteSectionParentNotebook |
| Get-MgBetaUserOnenoteSectionParentSectionGroup |
| Initialize-MgBetaMeAuthenticationHardwareOathMethod |
| Initialize-MgBetaSolutionBackupRestoreProtectionPolicy |
| Initialize-MgBetaSolutionBackupRestoreServiceApp |
| Initialize-MgBetaSolutionBackupRestoreSession |
| Initialize-MgBetaUserAuthenticationHardwareOathMethod |
| Invoke-MgBetaAcceptGroupEventExceptionOccurrence |
| Invoke-MgBetaAcceptGroupEventExceptionOccurrenceInstance |
| Invoke-MgBetaAcceptGroupEventExceptionOccurrenceInstanceTentatively |
| Invoke-MgBetaAcceptGroupEventExceptionOccurrenceTentatively |
| Invoke-MgBetaAcceptGroupEventInstance |
| Invoke-MgBetaAcceptGroupEventInstanceExceptionOccurrence |
| Invoke-MgBetaAcceptGroupEventInstanceExceptionOccurrenceTentatively |
| Invoke-MgBetaAcceptGroupEventInstanceTentatively |
| Invoke-MgBetaAcceptUserEventExceptionOccurrence |
| Invoke-MgBetaAcceptUserEventExceptionOccurrenceInstance |
| Invoke-MgBetaAcceptUserEventExceptionOccurrenceInstanceTentatively |
| Invoke-MgBetaAcceptUserEventExceptionOccurrenceTentatively |
| Invoke-MgBetaAcceptUserEventInstanceExceptionOccurrence |
| Invoke-MgBetaAcceptUserEventInstanceExceptionOccurrenceTentatively |
| Invoke-MgBetaAccountDeviceManagementWindowsAutopilotDeploymentProfileAssignedDevice |
| Invoke-MgBetaArchiveGroupSite |
| Invoke-MgBetaArchiveGroupSiteGetByPath |
| Invoke-MgBetaArchiveGroupTeam |
| Invoke-MgBetaArchiveGroupTeamChannel |
| Invoke-MgBetaArchiveGroupTeamPrimaryChannel |
| Invoke-MgBetaArchiveSite |
| Invoke-MgBetaArchiveSiteGetByPath |
| Invoke-MgBetaBulkUserManagedDeviceReprovisionCloudPc |
| Invoke-MgBetaBulkUserManagedDeviceRestoreCloudPc |
| Invoke-MgBetaCalendarUserCalendar |
| Invoke-MgBetaClockGroupTeamScheduleTimeCardIn |
| Invoke-MgBetaClockGroupTeamScheduleTimeCardOut |
| Invoke-MgBetaCreationMeAuthenticationFido2MethodOption |
| Invoke-MgBetaDeactivateMeAuthenticationHardwareOathMethod |
| Invoke-MgBetaDeactivateUserAuthenticationHardwareOathMethod |
| Invoke-MgBetaDeclineGroupEventExceptionOccurrence |
| Invoke-MgBetaDeclineGroupEventExceptionOccurrenceInstance |
| Invoke-MgBetaDeclineGroupEventInstance |
| Invoke-MgBetaDeclineGroupEventInstanceExceptionOccurrence |
| Invoke-MgBetaDeclineUserEventExceptionOccurrence |
| Invoke-MgBetaDeclineUserEventExceptionOccurrenceInstance |
| Invoke-MgBetaDeclineUserEventInstanceExceptionOccurrence |
| Invoke-MgBetaDismissGroupEventExceptionOccurrenceInstanceReminder |
| Invoke-MgBetaDismissGroupEventExceptionOccurrenceReminder |
| Invoke-MgBetaDismissGroupEventInstanceExceptionOccurrenceReminder |
| Invoke-MgBetaDismissGroupEventInstanceReminder |
| Invoke-MgBetaDismissUserEventExceptionOccurrenceInstanceReminder |
| Invoke-MgBetaDismissUserEventExceptionOccurrenceReminder |
| Invoke-MgBetaDismissUserEventInstanceExceptionOccurrenceReminder |
| Invoke-MgBetaDownloadUserManagedDevicePowerliftAppDiagnostic |
| Invoke-MgBetaForwardGroupEventExceptionOccurrence |
| Invoke-MgBetaForwardGroupEventExceptionOccurrenceInstance |
| Invoke-MgBetaForwardGroupEventInstance |
| Invoke-MgBetaForwardGroupEventInstanceExceptionOccurrence |
| Invoke-MgBetaForwardUserEventExceptionOccurrence |
| Invoke-MgBetaForwardUserEventExceptionOccurrenceInstance |
| Invoke-MgBetaForwardUserEventInstanceExceptionOccurrence |
| Invoke-MgBetaHaveGroupTeamChannel |
| Invoke-MgBetaHaveGroupTeamPrimaryChannel |
| Invoke-MgBetaMessageGroupTeamChannel |
| Invoke-MgBetaPreviewGroupOnenoteNotebookSectionGroupSectionPage |
| Invoke-MgBetaPreviewGroupOnenoteNotebookSectionPage |
| Invoke-MgBetaPreviewGroupOnenoteSectionGroupSectionPage |
| Invoke-MgBetaPreviewGroupOnenoteSectionPage |
| Invoke-MgBetaPreviewGroupSiteOnenoteNotebookSectionGroupSectionPage |
| Invoke-MgBetaPreviewGroupSiteOnenoteNotebookSectionPage |
| Invoke-MgBetaPreviewGroupSiteOnenotePage |
| Invoke-MgBetaPreviewGroupSiteOnenoteSectionGroupSectionPage |
| Invoke-MgBetaPreviewGroupSiteOnenoteSectionPage |
| Invoke-MgBetaPreviewUserOnenoteNotebookSectionGroupSectionPage |
| Invoke-MgBetaPreviewUserOnenoteNotebookSectionPage |
| Invoke-MgBetaPreviewUserOnenoteSectionGroupSectionPage |
| Invoke-MgBetaPreviewUserOnenoteSectionPage |
| Invoke-MgBetaShareGroupTeamSchedule |
| Invoke-MgBetaSnoozeGroupEventExceptionOccurrenceInstanceReminder |
| Invoke-MgBetaSnoozeGroupEventExceptionOccurrenceReminder |
| Invoke-MgBetaSnoozeGroupEventInstanceExceptionOccurrenceReminder |
| Invoke-MgBetaSnoozeGroupEventInstanceReminder |
| Invoke-MgBetaSnoozeUserEventExceptionOccurrenceInstanceReminder |
| Invoke-MgBetaSnoozeUserEventExceptionOccurrenceReminder |
| Invoke-MgBetaSnoozeUserEventInstanceExceptionOccurrenceReminder |
| Invoke-MgBetaSoftGroupTeamChannelMessageDelete |
| Invoke-MgBetaSoftGroupTeamChannelMessageReplyDelete |
| Invoke-MgBetaSoftGroupTeamPrimaryChannelMessageDelete |
| Invoke-MgBetaSoftGroupTeamPrimaryChannelMessageReplyDelete |
| Invoke-MgBetaUnarchiveGroupSite |
| Invoke-MgBetaUnarchiveGroupSiteGetByPath |
| Invoke-MgBetaUnarchiveGroupTeam |
| Invoke-MgBetaUnarchiveGroupTeamChannel |
| Invoke-MgBetaUnarchiveGroupTeamPrimaryChannel |
| Invoke-MgBetaUnarchiveSite |
| Invoke-MgBetaUnarchiveSiteGetByPath |
| Invoke-MgBetaUploadDirectoryPublicKeyInfrastructureCertificateBasedAuthConfiguration |
| New-MgBetaDirectoryAuthenticationMethodDeviceHardwareOathDevice |
| New-MgBetaDirectoryCertificateAuthorityMutualTlOauthConfiguration |
| New-MgBetaDirectoryPublicKeyInfrastructureCertificateBasedAuthConfiguration |
| New-MgBetaDirectoryPublicKeyInfrastructureCertificateBasedAuthConfigurationCertificateAuthority |
| New-MgBetaDirectoryTemplateDeviceFromTemplate |
| New-MgBetaDirectoryTemplateDeviceTemplate |
| New-MgBetaEducationReportReadingAssignmentSubmission |
| New-MgBetaEducationReportReflectCheck |
| New-MgBetaGroupEventAttachmentUploadSession |
| New-MgBetaGroupEventExceptionOccurrenceAttachmentUploadSession |
| New-MgBetaGroupEventExceptionOccurrenceInstanceAttachmentUploadSession |
| New-MgBetaGroupEventInstanceAttachmentUploadSession |
| New-MgBetaGroupEventInstanceExceptionOccurrenceAttachmentUploadSession |
| New-MgBetaGroupMember |
| New-MgBetaGroupOnenoteNotebookSectionGroupSection |
| New-MgBetaGroupOnenoteNotebookSectionGroupSectionPage |
| New-MgBetaGroupOnenoteNotebookSectionPage |
| New-MgBetaGroupOnenoteOperation |
| New-MgBetaGroupOnenoteResource |
| New-MgBetaGroupOnenoteSectionGroupSectionPage |
| New-MgBetaGroupTeamChannelEmail |
| New-MgBetaGroupTeamPrimaryChannelEmail |
| New-MgBetaIdentityProductChange |
| New-MgBetaMeAuthenticationEmailMethod |
| New-MgBetaMeAuthenticationHardwareOathMethod |
| New-MgBetaMeAuthenticationHardwareOathMethodDeviceHardwareOathDevice |
| New-MgBetaMeAuthenticationMethod |
| New-MgBetaMeAuthenticationOperation |
| New-MgBetaMeAuthenticationPasswordMethod |
| New-MgBetaMeAuthenticationPhoneMethod |
| New-MgBetaMeAuthenticationTemporaryAccessPassMethod |
| New-MgBetaReportHealthMonitoringAlert |
| New-MgBetaReportHealthMonitoringAlertConfiguration |
| New-MgBetaReportUserInsightDailyMfaTelecomFraud |
| New-MgBetaReportUserInsightMonthlyMfaRegisteredUser |
| New-MgBetaSecurityDataDiscoveryCloudAppDiscoveryUploadedStream |
| New-MgBetaSiteOnenoteNotebookSectionGroupSection |
| New-MgBetaSiteOnenoteNotebookSectionGroupSectionPage |
| New-MgBetaSiteOnenoteNotebookSectionPage |
| New-MgBetaSiteOnenoteOperation |
| New-MgBetaSiteOnenoteResource |
| New-MgBetaSiteOnenoteSectionGroupSectionPage |
| New-MgBetaSolutionBackupRestoreDriveProtectionUnitBulkAdditionJob |
| New-MgBetaSolutionBackupRestoreExchangeRestoreSessionMailboxRestoreArtifactBulkAdditionRequest |
| New-MgBetaSolutionBackupRestoreMailboxProtectionUnitBulkAdditionJob |
| New-MgBetaSolutionBackupRestoreOneDriveForBusinessRestoreSessionDriveRestoreArtifactBulkAdditionRequest |
| New-MgBetaSolutionBackupRestoreSharePointRestoreSessionSiteRestoreArtifactBulkAdditionRequest |
| New-MgBetaSolutionBackupRestoreSiteProtectionUnitBulkAdditionJob |
| New-MgBetaUserAuthenticationHardwareOathMethod |
| New-MgBetaUserAuthenticationHardwareOathMethodDeviceHardwareOathDevice |
| New-MgBetaUserEventExceptionOccurrenceAttachmentUploadSession |
| New-MgBetaUserEventExceptionOccurrenceInstanceAttachmentUploadSession |
| New-MgBetaUserEventInstanceExceptionOccurrenceAttachmentUploadSession |
| New-MgBetaUserManagedDeviceLogCollectionRequestDownloadUrl |
| New-MgBetaUserOnenoteNotebookSectionGroupSection |
| New-MgBetaUserOnenoteNotebookSectionGroupSectionPage |
| New-MgBetaUserOnenoteNotebookSectionPage |
| New-MgBetaUserOnenoteOperation |
| New-MgBetaUserOnenoteResource |
| New-MgBetaUserOnenoteSectionGroupSectionPage |
| Remove-MgBetaCommunicationCallContentSharingSessionPngOfCurrentSlide |
| Remove-MgBetaDirectoryAuthenticationMethodDevice |
| Remove-MgBetaDirectoryAuthenticationMethodDeviceHardwareOathDevice |
| Remove-MgBetaDirectoryCertificateAuthorityMutualTlOauthConfiguration |
| Remove-MgBetaDirectoryPublicKeyInfrastructure |
| Remove-MgBetaDirectoryPublicKeyInfrastructureCertificateBasedAuthConfiguration |
| Remove-MgBetaDirectoryPublicKeyInfrastructureCertificateBasedAuthConfigurationCertificateAuthority |
| Remove-MgBetaDirectoryTemplate |
| Remove-MgBetaDirectoryTemplateDeviceTemplate |
| Remove-MgBetaEducationReport |
| Remove-MgBetaEducationReportReadingAssignmentSubmission |
| Remove-MgBetaEducationReportReflectCheck |
| Remove-MgBetaGroupEventExceptionOccurrenceInstancePermanent |
| Remove-MgBetaGroupEventExceptionOccurrencePermanent |
| Remove-MgBetaGroupEventInstanceExceptionOccurrencePermanent |
| Remove-MgBetaGroupEventInstancePermanent |
| Remove-MgBetaGroupOnenote |
| Remove-MgBetaGroupOnenoteNotebookSection |
| Remove-MgBetaGroupOnenoteNotebookSectionGroup |
| Remove-MgBetaGroupOnenoteNotebookSectionGroupSection |
| Remove-MgBetaGroupOnenoteNotebookSectionGroupSectionPage |
| Remove-MgBetaGroupOnenoteNotebookSectionGroupSectionPageContent |
| Remove-MgBetaGroupOnenoteNotebookSectionPage |
| Remove-MgBetaGroupOnenoteNotebookSectionPageContent |
| Remove-MgBetaGroupOnenoteOperation |
| Remove-MgBetaGroupOnenoteResource |
| Remove-MgBetaGroupOnenoteResourceContent |
| Remove-MgBetaGroupOnenoteSectionGroupSection |
| Remove-MgBetaGroupOnenoteSectionGroupSectionPage |
| Remove-MgBetaGroupOnenoteSectionGroupSectionPageContent |
| Remove-MgBetaGroupOnenoteSectionPage |
| Remove-MgBetaGroupOnenoteSectionPageContent |
| Remove-MgBetaGroupTeamChannelAllMember |
| Remove-MgBetaGroupTeamChannelEmail |
| Remove-MgBetaGroupTeamPrimaryChannelAllMember |
| Remove-MgBetaGroupTeamPrimaryChannelEmail |
| Remove-MgBetaIdentityProductChange |
| Remove-MgBetaMeAuthentication |
| Remove-MgBetaMeAuthenticationEmailMethod |
| Remove-MgBetaMeAuthenticationFido2Method |
| Remove-MgBetaMeAuthenticationHardwareOathMethod |
| Remove-MgBetaMeAuthenticationHardwareOathMethodDevice |
| Remove-MgBetaMeAuthenticationHardwareOathMethodDeviceHardwareOathDevice |
| Remove-MgBetaMeAuthenticationMicrosoftAuthenticatorMethod |
| Remove-MgBetaMeAuthenticationOperation |
| Remove-MgBetaMeAuthenticationPasswordlessMicrosoftAuthenticatorMethod |
| Remove-MgBetaMeAuthenticationPhoneMethod |
| Remove-MgBetaMeAuthenticationPlatformCredentialMethod |
| Remove-MgBetaMeAuthenticationSoftwareOathMethod |
| Remove-MgBetaMeAuthenticationTemporaryAccessPassMethod |
| Remove-MgBetaMeAuthenticationWindowsHelloForBusinessMethod |
| Remove-MgBetaReportHealthMonitoringAlert |
| Remove-MgBetaReportHealthMonitoringAlertConfiguration |
| Remove-MgBetaReportUserInsightDailyMfaTelecomFraud |
| Remove-MgBetaReportUserInsightMonthlyMfaRegisteredUser |
| Remove-MgBetaSecurityDataDiscovery |
| Remove-MgBetaSecurityDataDiscoveryCloudAppDiscovery |
| Remove-MgBetaSecurityDataDiscoveryCloudAppDiscoveryUploadedStream |
| Remove-MgBetaSiteOnenote |
| Remove-MgBetaSiteOnenoteNotebookSection |
| Remove-MgBetaSiteOnenoteNotebookSectionGroup |
| Remove-MgBetaSiteOnenoteNotebookSectionGroupSection |
| Remove-MgBetaSiteOnenoteNotebookSectionGroupSectionPage |
| Remove-MgBetaSiteOnenoteNotebookSectionPage |
| Remove-MgBetaSiteOnenoteOperation |
| Remove-MgBetaSiteOnenoteResource |
| Remove-MgBetaSiteOnenoteSectionGroupSection |
| Remove-MgBetaSiteOnenoteSectionGroupSectionPage |
| Remove-MgBetaSiteOnenoteSectionPage |
| Remove-MgBetaSolutionBackupRestoreDriveProtectionUnitBulkAdditionJob |
| Remove-MgBetaSolutionBackupRestoreExchangeRestoreSessionMailboxRestoreArtifactBulkAdditionRequest |
| Remove-MgBetaSolutionBackupRestoreMailboxProtectionUnitBulkAdditionJob |
| Remove-MgBetaSolutionBackupRestoreOneDriveForBusinessRestoreSessionDriveRestoreArtifactBulkAdditionRequest |
| Remove-MgBetaSolutionBackupRestoreSharePointRestoreSessionSiteRestoreArtifactBulkAdditionRequest |
| Remove-MgBetaSolutionBackupRestoreSiteProtectionUnitBulkAdditionJob |
| Remove-MgBetaTeamChannelAllMember |
| Remove-MgBetaTeamPrimaryChannelAllMember |
| Remove-MgBetaTeamworkDeletedTeamChannelAllMember |
| Remove-MgBetaUserAuthenticationHardwareOathMethod |
| Remove-MgBetaUserAuthenticationHardwareOathMethodDevice |
| Remove-MgBetaUserAuthenticationHardwareOathMethodDeviceHardwareOathDevice |
| Remove-MgBetaUserByUserPrincipalName |
| Remove-MgBetaUserEventExceptionOccurrenceInstancePermanent |
| Remove-MgBetaUserEventExceptionOccurrencePermanent |
| Remove-MgBetaUserEventInstanceExceptionOccurrencePermanent |
| Remove-MgBetaUserManagedDeviceCategoryByRef |
| Remove-MgBetaUserOnenote |
| Remove-MgBetaUserOnenoteNotebookSection |
| Remove-MgBetaUserOnenoteNotebookSectionGroup |
| Remove-MgBetaUserOnenoteNotebookSectionGroupSection |
| Remove-MgBetaUserOnenoteNotebookSectionGroupSectionPage |
| Remove-MgBetaUserOnenoteNotebookSectionGroupSectionPageContent |
| Remove-MgBetaUserOnenoteNotebookSectionPage |
| Remove-MgBetaUserOnenoteNotebookSectionPageContent |
| Remove-MgBetaUserOnenoteOperation |
| Remove-MgBetaUserOnenoteResource |
| Remove-MgBetaUserOnenoteResourceContent |
| Remove-MgBetaUserOnenoteSectionGroupSection |
| Remove-MgBetaUserOnenoteSectionGroupSectionPage |
| Remove-MgBetaUserOnenoteSectionGroupSectionPageContent |
| Remove-MgBetaUserOnenoteSectionPage |
| Remove-MgBetaUserOnenoteSectionPageContent |
| Reset-MgBetaMeAuthenticationMethodPassword |
| Search-MgBetaSolutionBackupRestorePoint |
| Send-MgBetaGroupTeamActivityNotification |
| Set-MgBetaCommunicationCallContentSharingSessionPngOfCurrentSlide |
| Set-MgBetaDeviceManagementWindowsAutopilotDeploymentProfileAssignedDeviceResourceAccountToDevice |
| Set-MgBetaGroupOnenoteNotebookSectionGroupSectionPageContent |
| Set-MgBetaGroupOnenoteNotebookSectionPageContent |
| Set-MgBetaGroupOnenoteSectionGroupSectionPageContent |
| Set-MgBetaGroupTeamChannelMessageReaction |
| Set-MgBetaGroupTeamChannelMessageReplyReaction |
| Set-MgBetaGroupTeamPrimaryChannelMessageReaction |
| Set-MgBetaGroupTeamPrimaryChannelMessageReplyReaction |
| Set-MgBetaMeAuthenticationHardwareOathMethodAndActivate |
| Set-MgBetaMeAuthenticationHardwareOathMethodAndActivateBySerialNumber |
| Set-MgBetaSiteOnenoteNotebookSectionGroupSectionPageContent |
| Set-MgBetaSiteOnenoteNotebookSectionPageContent |
| Set-MgBetaSiteOnenoteSectionGroupSectionPageContent |
| Set-MgBetaUserAuthenticationHardwareOathMethodAndActivate |
| Set-MgBetaUserAuthenticationHardwareOathMethodAndActivateBySerialNumber |
| Set-MgBetaUserManagedDeviceCategoryByRef |
| Set-MgBetaUserOnenoteNotebookSectionGroupSectionPageContent |
| Set-MgBetaUserOnenoteNotebookSectionPageContent |
| Set-MgBetaUserOnenoteSectionGroupSectionPageContent |
| Set-MgBetaVirtualEventExternalEventInformation |
| Start-MgBetaCommunicationCallRecording |
| Start-MgBetaCommunicationCallTranscription |
| Start-MgBetaGroupTeamScheduleTimeCardBreak |
| Stop-MgBetaCommunicationCallRecording |
| Stop-MgBetaCommunicationCallTranscription |
| Stop-MgBetaGroupEventExceptionOccurrence |
| Stop-MgBetaGroupEventExceptionOccurrenceInstance |
| Stop-MgBetaGroupEventInstance |
| Stop-MgBetaGroupEventInstanceExceptionOccurrence |
| Stop-MgBetaGroupTeamScheduleTimeCardBreak |
| Stop-MgBetaUserEventExceptionOccurrence |
| Stop-MgBetaUserEventExceptionOccurrenceInstance |
| Stop-MgBetaUserEventInstanceExceptionOccurrence |
| Undo-MgBetaGroupTeamChannelMessageReplySoftDelete |
| Undo-MgBetaGroupTeamChannelMessageSoftDelete |
| Undo-MgBetaGroupTeamPrimaryChannelMessageReplySoftDelete |
| Undo-MgBetaGroupTeamPrimaryChannelMessageSoftDelete |
| Update-MgBetaDeviceManagementWindowsAutopilotDeploymentProfileAssignedDeviceProperty |
| Update-MgBetaDirectoryAuthenticationMethodDevice |
| Update-MgBetaDirectoryAuthenticationMethodDeviceHardwareOathDevice |
| Update-MgBetaDirectoryAuthenticationMethodDeviceHardwareOathDeviceAssignToMailboxSetting |
| Update-MgBetaDirectoryCertificateAuthorityMutualTlOauthConfiguration |
| Update-MgBetaDirectoryPublicKeyInfrastructure |
| Update-MgBetaDirectoryPublicKeyInfrastructureCertificateBasedAuthConfiguration |
| Update-MgBetaDirectoryPublicKeyInfrastructureCertificateBasedAuthConfigurationCertificateAuthority |
| Update-MgBetaDirectoryTemplate |
| Update-MgBetaDirectoryTemplateDeviceTemplate |
| Update-MgBetaEducationReport |
| Update-MgBetaEducationReportReadingAssignmentSubmission |
| Update-MgBetaEducationReportReflectCheck |
| Update-MgBetaGroupOnenote |
| Update-MgBetaGroupOnenoteNotebookSection |
| Update-MgBetaGroupOnenoteNotebookSectionGroup |
| Update-MgBetaGroupOnenoteNotebookSectionGroupSection |
| Update-MgBetaGroupOnenoteOperation |
| Update-MgBetaGroupOnenoteResource |
| Update-MgBetaGroupOnenoteSectionGroupSection |
| Update-MgBetaGroupTeamInstalledApp |
| Update-MgBetaIdentityProductChange |
| Update-MgBetaMeAuthentication |
| Update-MgBetaMeAuthenticationEmailMethod |
| Update-MgBetaMeAuthenticationHardwareOathMethodDevice |
| Update-MgBetaMeAuthenticationHardwareOathMethodDeviceAssignToMailboxSetting |
| Update-MgBetaMeAuthenticationHardwareOathMethodDeviceHardwareOathDevice |
| Update-MgBetaMeAuthenticationHardwareOathMethodDeviceHardwareOathDeviceAssignToMailboxSetting |
| Update-MgBetaMeAuthenticationMethod |
| Update-MgBetaMeAuthenticationOperation |
| Update-MgBetaMeAuthenticationPhoneMethod |
| Update-MgBetaMeAuthenticationRequirement |
| Update-MgBetaMeAuthenticationSignInPreference |
| Update-MgBetaReportHealthMonitoringAlert |
| Update-MgBetaReportHealthMonitoringAlertConfiguration |
| Update-MgBetaReportUserInsightDailyMfaTelecomFraud |
| Update-MgBetaReportUserInsightMonthlyMfaRegisteredUser |
| Update-MgBetaSecurityDataDiscovery |
| Update-MgBetaSecurityDataDiscoveryCloudAppDiscovery |
| Update-MgBetaSecurityDataDiscoveryCloudAppDiscoveryUploadedStream |
| Update-MgBetaSiteOnenote |
| Update-MgBetaSiteOnenoteNotebookSection |
| Update-MgBetaSiteOnenoteNotebookSectionGroup |
| Update-MgBetaSiteOnenoteNotebookSectionGroupSection |
| Update-MgBetaSiteOnenoteOperation |
| Update-MgBetaSiteOnenoteResource |
| Update-MgBetaSiteOnenoteSectionGroupSection |
| Update-MgBetaSolutionBackupRestoreDriveProtectionUnitBulkAdditionJob |
| Update-MgBetaSolutionBackupRestoreExchangeRestoreSessionMailboxRestoreArtifactBulkAdditionRequest |
| Update-MgBetaSolutionBackupRestoreMailboxProtectionUnitBulkAdditionJob |
| Update-MgBetaSolutionBackupRestoreOneDriveForBusinessRestoreSessionDriveRestoreArtifactBulkAdditionRequest |
| Update-MgBetaSolutionBackupRestoreSharePointRestoreSessionSiteRestoreArtifactBulkAdditionRequest |
| Update-MgBetaSolutionBackupRestoreSiteProtectionUnitBulkAdditionJob |
| Update-MgBetaUserAuthenticationHardwareOathMethodDevice |
| Update-MgBetaUserAuthenticationHardwareOathMethodDeviceAssignToMailboxSetting |
| Update-MgBetaUserAuthenticationHardwareOathMethodDeviceHardwareOathDevice |
| Update-MgBetaUserAuthenticationHardwareOathMethodDeviceHardwareOathDeviceAssignToMailboxSetting |
| Update-MgBetaUserAuthenticationRequirement |
| Update-MgBetaUserByUserPrincipalName |
| Update-MgBetaUserMailFolderChildFolderMessageReadState |
| Update-MgBetaUserMailFolderMessageReadState |
| Update-MgBetaUserOnenote |
| Update-MgBetaUserOnenoteNotebookSection |
| Update-MgBetaUserOnenoteNotebookSectionGroup |
| Update-MgBetaUserOnenoteNotebookSectionGroupSection |
| Update-MgBetaUserOnenoteOperation |
| Update-MgBetaUserOnenoteResource |
| Update-MgBetaUserOnenoteSectionGroupSection |

### Removed Cmdlets (0)

No cmdlets removed.

### Modified Cmdlets (1796)

| Command | Changes |
|---------|---------|
| Add-MgBetaGroupDriveListContentTypeCopy | Minor changes |
| Add-MgBetaGroupDriveListContentTypeCopyFromContentTypeHub | Minor changes |
| Add-MgBetaGroupSite | Minor changes |
| Add-MgBetaGroupSiteContentModelToDrive | Minor changes |
| Add-MgBetaGroupSiteContentTypeCopy | Minor changes |
| Add-MgBetaGroupSiteContentTypeCopyFromContentTypeHub | Minor changes |
| Add-MgBetaGroupSiteListContentTypeCopy | Minor changes |
| Add-MgBetaGroupSiteListContentTypeCopyFromContentTypeHub | Minor changes |
| Add-MgBetaUserChatMember | Minor changes |
| Add-MgBetaUserDriveListContentTypeCopy | Minor changes |
| Add-MgBetaUserDriveListContentTypeCopyFromContentTypeHub | Minor changes |
| Add-MgBetaUserFollowedSite | Minor changes |
| Clear-MgBetaDeviceAppManagementWindowsInformationProtectionDeviceRegistration | Minor changes |
| Clear-MgBetaUserChatMessageReaction | Minor changes |
| Clear-MgBetaUserChatMessageReplyReaction | Minor changes |
| Clear-MgBetaUserManagedDevice | Minor changes |
| Clear-MgBetaUserPresence | Minor changes |
| Clear-MgBetaUserPresenceUserPreferredPresence | Minor changes |
| Complete-MgBetaUserChatMigration | Minor changes |
| Complete-MgBetaUserOutlookTask | Minor changes |
| Complete-MgBetaUserOutlookTaskFolderTask | Minor changes |
| Complete-MgBetaUserOutlookTaskGroupTaskFolderTask | Minor changes |
| Confirm-MgBetaGroupSiteInformationProtectionSignature | Minor changes |
| Confirm-MgBetaUserInformationProtectionSignature | Minor changes |
| Convert-MgBetaDeviceAppManagementMobileAppFromMobileAppCatalogPackage | Minor changes |
| Copy-MgBetaGroupDriveItem | Minor changes |
| Copy-MgBetaGroupDriveListContentTypeToDefaultContentLocation | Minor changes |
| Copy-MgBetaGroupDriveRoot | Minor changes |
| Copy-MgBetaGroupOnenoteNotebook | Minor changes |
| Copy-MgBetaGroupOnenotePageToSection | Minor changes |
| Copy-MgBetaGroupOnenoteSectionToNotebook | Minor changes |
| Copy-MgBetaGroupOnenoteSectionToSectionGroup | Minor changes |
| Copy-MgBetaGroupSiteContentTypeToDefaultContentLocation | Minor changes |
| Copy-MgBetaGroupSiteListContentTypeToDefaultContentLocation | Minor changes |
| Copy-MgBetaSiteOnenoteNotebook | Minor changes |
| Copy-MgBetaSiteOnenoteNotebookSectionGroupSectionPageToSection | Minor changes |
| Copy-MgBetaSiteOnenoteNotebookSectionGroupSectionToNotebook | Minor changes |
| Copy-MgBetaSiteOnenoteNotebookSectionGroupSectionToSectionGroup | Minor changes |
| Copy-MgBetaSiteOnenoteNotebookSectionPageToSection | Minor changes |
| Copy-MgBetaSiteOnenoteNotebookSectionToNotebook | Minor changes |
| Copy-MgBetaSiteOnenoteNotebookSectionToSectionGroup | Minor changes |
| Copy-MgBetaSiteOnenotePageToSection | Minor changes |
| Copy-MgBetaSiteOnenoteSectionGroupSectionPageToSection | Minor changes |
| Copy-MgBetaSiteOnenoteSectionGroupSectionToNotebook | Minor changes |
| Copy-MgBetaSiteOnenoteSectionGroupSectionToSectionGroup | Minor changes |
| Copy-MgBetaSiteOnenoteSectionPageToSection | Minor changes |
| Copy-MgBetaSiteOnenoteSectionToNotebook | Minor changes |
| Copy-MgBetaSiteOnenoteSectionToSectionGroup | Minor changes |
| Copy-MgBetaUserDriveItem | Minor changes |
| Copy-MgBetaUserDriveListContentTypeToDefaultContentLocation | Minor changes |
| Copy-MgBetaUserDriveRoot | Minor changes |
| Copy-MgBetaUserMailFolder | Minor changes |
| Copy-MgBetaUserMailFolderChildFolder | Minor changes |
| Copy-MgBetaUserMailFolderChildFolderMessage | Minor changes |
| Copy-MgBetaUserMailFolderMessage | Minor changes |
| Copy-MgBetaUserMessage | Minor changes |
| Copy-MgBetaUserOnenoteNotebook | Minor changes |
| Copy-MgBetaUserOnenotePageToSection | Minor changes |
| Copy-MgBetaUserOnenoteSectionToNotebook | Minor changes |
| Copy-MgBetaUserOnenoteSectionToSectionGroup | Minor changes |
| Disable-MgBetaUserAuthenticationMethodSmsSignIn | Minor changes |
| Disable-MgBetaUserManagedDevice | Minor changes |
| Disable-MgBetaUserManagedDeviceLostMode | Minor changes |
| Enable-MgBetaUserAuthenticationMethodSmsSignIn | Minor changes |
| Enable-MgBetaUserManagedDeviceLostMode | Minor changes |
| Export-MgBetaDeviceManagementDepOnboardingSettingEnrollmentProfileMobileConfig | Minor changes |
| Export-MgBetaSecurityCaseEdiscoveryCaseSearchReport | Minor changes |
| Export-MgBetaSecurityCaseEdiscoveryCaseSearchResult | Minor changes |
| Find-MgBetaUserManagedDevice | Minor changes |
| Get-MgBetaAdminEdgeInternetExplorerModeSiteList | Minor changes |
| Get-MgBetaAdminEdgeInternetExplorerModeSiteListSharedCookie | Minor changes |
| Get-MgBetaAdministrativeUnitMemberAsDevice | Minor changes |
| Get-MgBetaAdministrativeUnitMemberAsUser | Minor changes |
| Get-MgBetaAgreementFileLocalization | Minor changes |
| Get-MgBetaAgreementFileLocalizationVersion | Minor changes |
| Get-MgBetaAppCatalogTeamAppDefinitionDashboardCard | Minor changes |
| Get-MgBetaApplicationFederatedIdentityCredential | Minor changes |
| Get-MgBetaApplicationOwnerAsEndpoint | Minor changes |
| Get-MgBetaApplicationSynchronizationJobSchemaDirectory | Minor changes |
| Get-MgBetaApplicationSynchronizationTemplateSchemaDirectory | Minor changes |
| Get-MgBetaAuditLogDirectoryProvisioning | Minor changes |
| Get-MgBetaBookingBusiness | Minor changes |
| Get-MgBetaBookingBusinessAppointment | Minor changes |
| Get-MgBetaBookingBusinessStaffMember | Minor changes |
| Get-MgBetaBusinessFlowTemplate | Minor changes |
| Get-MgBetaChatInstalledApp | Minor changes |
| Get-MgBetaChatMember | Minor changes |
| Get-MgBetaChatMessage | Minor changes |
| Get-MgBetaChatMessageCount | Minor changes |
| Get-MgBetaChatMessageDelta | Minor changes |
| Get-MgBetaChatMessageHostedContent | Minor changes |
| Get-MgBetaChatMessageHostedContentCount | Minor changes |
| Get-MgBetaChatMessageReply | Minor changes |
| Get-MgBetaChatTab | Minor changes |
| Get-MgBetaCommunicationCallContentSharingSession | Minor changes |
| Get-MgBetaCommunicationCallParticipant | Minor changes |
| Get-MgBetaCommunicationOnlineMeetingAttendanceReportAttendanceRecord | Minor changes |
| Get-MgBetaCommunicationOnlineMeetingRegistrationCustomQuestion | Minor changes |
| Get-MgBetaCommunicationOnlineMeetingRegistrationRegistrant | Minor changes |
| Get-MgBetaComplianceEdiscoveryCaseCustodian | Minor changes |
| Get-MgBetaComplianceEdiscoveryCaseLegalHoldSiteSource | Minor changes |
| Get-MgBetaComplianceEdiscoveryCaseLegalHoldUnifiedGroupSource | Minor changes |
| Get-MgBetaComplianceEdiscoveryCaseOperation | Minor changes |
| Get-MgBetaComplianceEdiscoveryCaseOperationAsCaseExportOperation | Minor changes |
| Get-MgBetaComplianceEdiscoveryCaseReviewSet | Minor changes |
| Get-MgBetaComplianceEdiscoveryCaseSourceCollectionAdditionalSource | Minor changes |
| Get-MgBetaComplianceEdiscoveryCaseSourceCollectionCustodianSource | Minor changes |
| Get-MgBetaContact | Minor changes |
| Get-MgBetaContactDirectReportAsUser | Minor changes |
| Get-MgBetaContactMemberOfAsAdministrativeUnit | Minor changes |
| Get-MgBetaDataPolicyOperation | Minor changes |
| Get-MgBetaDeviceAppManagement | Minor changes |
| Get-MgBetaDeviceAppManagementAndroidManagedAppProtection | Minor changes |
| Get-MgBetaDeviceAppManagementAndroidManagedAppProtectionApp | Minor changes |
| Get-MgBetaDeviceAppManagementAndroidManagedAppProtectionAppCount | Minor changes |
| Get-MgBetaDeviceAppManagementAndroidManagedAppProtectionAssignment | Minor changes |
| Get-MgBetaDeviceAppManagementAndroidManagedAppProtectionAssignmentCount | Minor changes |
| Get-MgBetaDeviceAppManagementAndroidManagedAppProtectionCount | Minor changes |
| Get-MgBetaDeviceAppManagementAndroidManagedAppProtectionDeploymentSummary | Minor changes |
| Get-MgBetaDeviceAppManagementDefaultManagedAppProtection | Minor changes |
| Get-MgBetaDeviceAppManagementDefaultManagedAppProtectionApp | Minor changes |
| Get-MgBetaDeviceAppManagementDefaultManagedAppProtectionAppCount | Minor changes |
| Get-MgBetaDeviceAppManagementDefaultManagedAppProtectionCount | Minor changes |
| Get-MgBetaDeviceAppManagementDefaultManagedAppProtectionDeploymentSummary | Minor changes |
| Get-MgBetaDeviceAppManagementEnterpriseCodeSigningCertificate | Minor changes |
| Get-MgBetaDeviceAppManagementEnterpriseCodeSigningCertificateCount | Minor changes |
| Get-MgBetaDeviceAppManagementManagedAppPolicy | Minor changes |
| Get-MgBetaDeviceAppManagementManagedAppPolicyCount | Minor changes |
| Get-MgBetaDeviceAppManagementManagedAppRegistration | Minor changes |
| Get-MgBetaDeviceAppManagementManagedAppRegistrationAppliedPolicy | Minor changes |
| Get-MgBetaDeviceAppManagementManagedAppRegistrationAppliedPolicyCount | Minor changes |
| Get-MgBetaDeviceAppManagementManagedAppRegistrationCount | Minor changes |
| Get-MgBetaDeviceAppManagementManagedAppRegistrationIntendedPolicy | Minor changes |
| Get-MgBetaDeviceAppManagementManagedAppRegistrationIntendedPolicyCount | Minor changes |
| Get-MgBetaDeviceAppManagementManagedAppRegistrationOperation | Minor changes |
| Get-MgBetaDeviceAppManagementManagedAppRegistrationOperationCount | Minor changes |
| Get-MgBetaDeviceAppManagementManagedAppRegistrationUserIdWithFlaggedAppRegistration | Minor changes |
| Get-MgBetaDeviceAppManagementManagedAppStatus | Minor changes |
| Get-MgBetaDeviceAppManagementManagedAppStatusCount | Minor changes |
| Get-MgBetaDeviceAppManagementManagedEBook | Minor changes |
| Get-MgBetaDeviceAppManagementManagedEBookAssignment | Minor changes |
| Get-MgBetaDeviceAppManagementManagedEBookAssignmentCount | Minor changes |
| Get-MgBetaDeviceAppManagementManagedEBookCategory | Minor changes |
| Get-MgBetaDeviceAppManagementManagedEBookCategoryCount | Minor changes |
| Get-MgBetaDeviceAppManagementManagedEBookCount | Minor changes |
| Get-MgBetaDeviceAppManagementManagedEBookDeviceState | Minor changes |
| Get-MgBetaDeviceAppManagementManagedEBookDeviceStateCount | Minor changes |
| Get-MgBetaDeviceAppManagementManagedEBookInstallSummary | Minor changes |
| Get-MgBetaDeviceAppManagementManagedEBookUserStateSummary | Minor changes |
| Get-MgBetaDeviceAppManagementManagedEBookUserStateSummaryCount | Minor changes |
| Get-MgBetaDeviceAppManagementManagedEBookUserStateSummaryDeviceState | Minor changes |
| Get-MgBetaDeviceAppManagementManagedEBookUserStateSummaryDeviceStateCount | Minor changes |
| Get-MgBetaDeviceAppManagementMdmWindowsInformationProtectionPolicy | Minor changes |
| Get-MgBetaDeviceAppManagementMdmWindowsInformationProtectionPolicyAssignment | Minor changes |
| Get-MgBetaDeviceAppManagementMdmWindowsInformationProtectionPolicyAssignmentCount | Minor changes |
| Get-MgBetaDeviceAppManagementMdmWindowsInformationProtectionPolicyCount | Minor changes |
| Get-MgBetaDeviceAppManagementMdmWindowsInformationProtectionPolicyExemptAppLockerFile | Minor changes |
| Get-MgBetaDeviceAppManagementMdmWindowsInformationProtectionPolicyExemptAppLockerFileCount | Minor changes |
| Get-MgBetaDeviceAppManagementMdmWindowsInformationProtectionPolicyProtectedAppLockerFile | Minor changes |
| Get-MgBetaDeviceAppManagementMdmWindowsInformationProtectionPolicyProtectedAppLockerFileCount | Minor changes |
| Get-MgBetaDeviceAppManagementMobileApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsAndroidForWorkApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsAndroidForWorkAppCategory | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsAndroidForWorkAppRelationship | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsAndroidLobApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsAndroidLobAppContentVersionFile | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsAndroidLobAppRelationship | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsAndroidManagedStoreApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsAndroidStoreApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsAndroidStoreAppCategory | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsAndroidStoreAppRelationship | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsIoStoreApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsIoStoreAppCategory | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsIoVppApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsIoVppAppCategory | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsMacOSDmgApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsMacOSDmgAppAssignment | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsMacOSDmgAppRelationship | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsMacOSLobApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsMacOSLobAppContentVersionFile | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsMacOSLobAppRelationship | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsMacOSPkgApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsMacOSPkgAppContentVersion | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsManagedAndroidLobApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsManagedAndroidLobAppCategory | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsManagedAndroidLobAppContentVersionContainedApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsManagedMobileLobApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsManagedMobileLobAppAssignment | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsManagedMobileLobAppContentVersionContainedApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsManagedMobileLobAppRelationship | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsManagediOSLobApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsManagediOSLobAppAssignment | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsManagediOSLobAppContentVersion | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsMicrosoftStoreForBusinessApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsWin32LobApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsWin32LobAppAssignment | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsWin32LobAppContentVersionFile | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsWinGetApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsWindowStoreApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsWindowStoreAppRelationship | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsWindowsAppX | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsWindowsAppXAssignment | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsWindowsAppXCategory | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsWindowsAppXContentVersionFile | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsWindowsAppXRelationship | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsWindowsMobileMsi | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsWindowsMobileMsiContentVersionFile | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsWindowsUniversalAppX | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsWindowsUniversalAppXContentVersion | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsWindowsUniversalAppXContentVersionContainedApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsWindowsWebApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsWindowsWebAppCategory | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsiOSLobApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsiOSLobAppContentVersion | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsiOSLobAppContentVersionContainedApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAsiOSLobAppRelationship | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAssignment | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppAssignmentCount | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppCategory | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppConfiguration | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppConfigurationAssignment | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppConfigurationAssignmentCount | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppConfigurationCount | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppConfigurationDeviceStatus | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppConfigurationDeviceStatusCount | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppConfigurationDeviceStatusSummary | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppConfigurationUserStatusCount | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppConfigurationUserStatusSummary | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppCount | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppCountAsAndroidForWorkApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppCountAsAndroidLobApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppCountAsAndroidManagedStoreApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppCountAsAndroidStoreApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppCountAsIoStoreApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppCountAsIoVppApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppCountAsMacOSDmgApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppCountAsMacOSLobApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppCountAsMacOSPkgApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppCountAsManagedAndroidLobApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppCountAsManagedMobileLobApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppCountAsManagediOSLobApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppCountAsMicrosoftStoreForBusinessApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppCountAsWin32LobApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppCountAsWinGetApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppCountAsWindowStoreApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppCountAsWindowsAppX | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppCountAsWindowsMobileMsi | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppCountAsWindowsUniversalAppX | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppCountAsWindowsWebApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppCountAsiOSLobApp | Minor changes |
| Get-MgBetaDeviceAppManagementMobileAppRelationship | Minor changes |
| Get-MgBetaDeviceAppManagementPolicySetAssignment | Minor changes |
| Get-MgBetaDeviceAppManagementPolicySetAssignmentCount | Minor changes |
| Get-MgBetaDeviceAppManagementPolicySetCount | Minor changes |
| Get-MgBetaDeviceAppManagementPolicySetItem | Minor changes |
| Get-MgBetaDeviceAppManagementPolicySetItemCount | Minor changes |
| Get-MgBetaDeviceAppManagementSymantecCodeSigningCertificate | Minor changes |
| Get-MgBetaDeviceAppManagementTargetedManagedAppConfiguration | Minor changes |
| Get-MgBetaDeviceAppManagementTargetedManagedAppConfigurationApp | Minor changes |
| Get-MgBetaDeviceAppManagementTargetedManagedAppConfigurationAppCount | Minor changes |
| Get-MgBetaDeviceAppManagementTargetedManagedAppConfigurationAssignment | Minor changes |
| Get-MgBetaDeviceAppManagementTargetedManagedAppConfigurationAssignmentCount | Minor changes |
| Get-MgBetaDeviceAppManagementTargetedManagedAppConfigurationCount | Minor changes |
| Get-MgBetaDeviceAppManagementTargetedManagedAppConfigurationDeploymentSummary | Minor changes |
| Get-MgBetaDeviceAppManagementTargetedManagedAppConfigurationSetting | Minor changes |
| Get-MgBetaDeviceAppManagementTargetedManagedAppConfigurationSettingCount | Minor changes |
| Get-MgBetaDeviceAppManagementTargetedManagedAppConfigurationSettingDefinition | Minor changes |
| Get-MgBetaDeviceAppManagementTargetedManagedAppConfigurationSettingDefinitionCount | Minor changes |
| Get-MgBetaDeviceAppManagementTask | Minor changes |
| Get-MgBetaDeviceAppManagementTaskCount | Minor changes |
| Get-MgBetaDeviceAppManagementVppToken | Minor changes |
| Get-MgBetaDeviceAppManagementVppTokenCount | Minor changes |
| Get-MgBetaDeviceAppManagementVppTokenLicenseForApp | Minor changes |
| Get-MgBetaDeviceAppManagementWdacSupplementalPolicy | Minor changes |
| Get-MgBetaDeviceAppManagementWdacSupplementalPolicyAssignment | Minor changes |
| Get-MgBetaDeviceAppManagementWdacSupplementalPolicyAssignmentCount | Minor changes |
| Get-MgBetaDeviceAppManagementWdacSupplementalPolicyCount | Minor changes |
| Get-MgBetaDeviceAppManagementWdacSupplementalPolicyDeploySummary | Minor changes |
| Get-MgBetaDeviceAppManagementWdacSupplementalPolicyDeviceStatus | Minor changes |
| Get-MgBetaDeviceAppManagementWindowsInformationProtectionDeviceRegistration | Minor changes |
| Get-MgBetaDeviceAppManagementWindowsInformationProtectionDeviceRegistrationCount | Minor changes |
| Get-MgBetaDeviceAppManagementWindowsInformationProtectionPolicy | Minor changes |
| Get-MgBetaDeviceAppManagementWindowsInformationProtectionPolicyAssignment | Minor changes |
| Get-MgBetaDeviceAppManagementWindowsInformationProtectionPolicyAssignmentCount | Minor changes |
| Get-MgBetaDeviceAppManagementWindowsInformationProtectionPolicyCount | Minor changes |
| Get-MgBetaDeviceAppManagementWindowsInformationProtectionPolicyExemptAppLockerFile | Minor changes |
| Get-MgBetaDeviceAppManagementWindowsInformationProtectionPolicyExemptAppLockerFileCount | Minor changes |
| Get-MgBetaDeviceAppManagementWindowsInformationProtectionPolicyProtectedAppLockerFile | Minor changes |
| Get-MgBetaDeviceAppManagementWindowsInformationProtectionPolicyProtectedAppLockerFileCount | Minor changes |
| Get-MgBetaDeviceAppManagementWindowsInformationProtectionWipeAction | Minor changes |
| Get-MgBetaDeviceAppManagementWindowsInformationProtectionWipeActionCount | Minor changes |
| Get-MgBetaDeviceAppManagementWindowsManagedAppProtection | Minor changes |
| Get-MgBetaDeviceAppManagementWindowsManagedAppProtectionApp | Minor changes |
| Get-MgBetaDeviceAppManagementWindowsManagedAppProtectionAppCount | Minor changes |
| Get-MgBetaDeviceAppManagementWindowsManagedAppProtectionAssignment | Minor changes |
| Get-MgBetaDeviceAppManagementWindowsManagedAppProtectionAssignmentCount | Minor changes |
| Get-MgBetaDeviceAppManagementWindowsManagedAppProtectionCount | Minor changes |
| Get-MgBetaDeviceAppManagementWindowsManagementApp | Minor changes |
| Get-MgBetaDeviceAppManagementiOSLobAppProvisioningConfigurationAssignment | Minor changes |
| Get-MgBetaDeviceAppManagementiOSLobAppProvisioningConfigurationAssignmentCount | Minor changes |
| Get-MgBetaDeviceAppManagementiOSLobAppProvisioningConfigurationDeviceStatus | Minor changes |
| Get-MgBetaDeviceAppManagementiOSLobAppProvisioningConfigurationDeviceStatusCount | Minor changes |
| Get-MgBetaDeviceAppManagementiOSLobAppProvisioningConfigurationGroupAssignment | Minor changes |
| Get-MgBetaDeviceAppManagementiOSLobAppProvisioningConfigurationGroupAssignmentCount | Minor changes |
| Get-MgBetaDeviceAppManagementiOSLobAppProvisioningConfigurationUserStatus | Minor changes |
| Get-MgBetaDeviceAppManagementiOSLobAppProvisioningConfigurationUserStatusCount | Minor changes |
| Get-MgBetaDeviceAppManagementiOSManagedAppProtection | Minor changes |
| Get-MgBetaDeviceAppManagementiOSManagedAppProtectionApp | Minor changes |
| Get-MgBetaDeviceAppManagementiOSManagedAppProtectionAppCount | Minor changes |
| Get-MgBetaDeviceAppManagementiOSManagedAppProtectionAssignment | Minor changes |
| Get-MgBetaDeviceAppManagementiOSManagedAppProtectionAssignmentCount | Minor changes |
| Get-MgBetaDeviceAppManagementiOSManagedAppProtectionCount | Minor changes |
| Get-MgBetaDeviceAppManagementiOSManagedAppProtectionDeploymentSummary | Minor changes |
| Get-MgBetaDeviceManagementAdvancedThreatProtectionOnboardingStateSummaryAdvancedThreatProtectionOnboardingDeviceSettingState | Minor changes |
| Get-MgBetaDeviceManagementAndroidDeviceOwnerEnrollmentProfile | Minor changes |
| Get-MgBetaDeviceManagementAndroidForWorkEnrollmentProfile | Minor changes |
| Get-MgBetaDeviceManagementAndroidManagedStoreAppConfigurationSchema | Minor changes |
| Get-MgBetaDeviceManagementAssignmentFilter | Minor changes |
| Get-MgBetaDeviceManagementAuditEvent | Minor changes |
| Get-MgBetaDeviceManagementCartToClassAssociation | Minor changes |
| Get-MgBetaDeviceManagementComanagedDevice | Minor changes |
| Get-MgBetaDeviceManagementComanagedDeviceLogCollectionRequest | Minor changes |
| Get-MgBetaDeviceManagementComanagedDeviceManagedDeviceMobileAppConfigurationState | Minor changes |
| Get-MgBetaDeviceManagementComplianceManagementPartner | Minor changes |
| Get-MgBetaDeviceManagementCompliancePolicy | Minor changes |
| Get-MgBetaDeviceManagementCompliancePolicySetting | Minor changes |
| Get-MgBetaDeviceManagementCompliancePolicySettingDefinition | Minor changes |
| Get-MgBetaDeviceManagementComplianceSetting | Minor changes |
| Get-MgBetaDeviceManagementConfigurationPolicyTemplate | Minor changes |
| Get-MgBetaDeviceManagementDataSharingConsent | Minor changes |
| Get-MgBetaDeviceManagementDepOnboardingSettingEncryptionPublicKey | Minor changes |
| Get-MgBetaDeviceManagementDepOnboardingSettingEnrollmentProfile | Minor changes |
| Get-MgBetaDeviceManagementDepOnboardingSettingExpiringVppTokenCount | Minor changes |
| Get-MgBetaDeviceManagementDetectedApp | Minor changes |
| Get-MgBetaDeviceManagementDeviceCompliancePolicy | Minor changes |
| Get-MgBetaDeviceManagementDeviceCompliancePolicyDeviceSettingStateSummary | Minor changes |
| Get-MgBetaDeviceManagementDeviceCompliancePolicySettingStateSummary | Minor changes |
| Get-MgBetaDeviceManagementDeviceConfigurationAssignment | Minor changes |
| Get-MgBetaDeviceManagementDeviceConfigurationConflictSummary | Minor changes |
| Get-MgBetaDeviceManagementDeviceConfigurationGroupAssignment | Minor changes |
| Get-MgBetaDeviceManagementDeviceConfigurationManagedDeviceCertificateState | Minor changes |
| Get-MgBetaDeviceManagementDeviceEnrollmentConfigurationAssignment | Minor changes |
| Get-MgBetaDeviceManagementDeviceHealthScriptAssignment | Minor changes |
| Get-MgBetaDeviceManagementDeviceShellScriptAssignment | Minor changes |
| Get-MgBetaDeviceManagementDeviceShellScriptUserRunStateDeviceRunState | Minor changes |
| Get-MgBetaDeviceManagementDomainJoinConnector | Minor changes |
| Get-MgBetaDeviceManagementExchangeOnPremisePolicy | Minor changes |
| Get-MgBetaDeviceManagementGroupPolicyCategoryDefinition | Minor changes |
| Get-MgBetaDeviceManagementGroupPolicyConfigurationAssignment | Minor changes |
| Get-MgBetaDeviceManagementGroupPolicyConfigurationDefinitionValuePresentationValue | Minor changes |
| Get-MgBetaDeviceManagementGroupPolicyDefinitionFile | Minor changes |
| Get-MgBetaDeviceManagementGroupPolicyDefinitionPreviouVersionDefinitionNextVersionDefinitionPresentation | Minor changes |
| Get-MgBetaDeviceManagementGroupPolicyMigrationReport | Minor changes |
| Get-MgBetaDeviceManagementGroupPolicyObjectFile | Minor changes |
| Get-MgBetaDeviceManagementGroupPolicyUploadedDefinitionFile | Minor changes |
| Get-MgBetaDeviceManagementGroupPolicyUploadedDefinitionFileDefinition | Minor changes |
| Get-MgBetaDeviceManagementImportedDeviceIdentity | Minor changes |
| Get-MgBetaDeviceManagementIntentAssignment | Minor changes |
| Get-MgBetaDeviceManagementIntentCategory | Minor changes |
| Get-MgBetaDeviceManagementIntentDeviceSettingStateSummary | Minor changes |
| Get-MgBetaDeviceManagementIntuneBrandingProfile | Minor changes |
| Get-MgBetaDeviceManagementIoUpdateStatus | Minor changes |
| Get-MgBetaDeviceManagementMacOSSoftwareUpdateAccountSummary | Minor changes |
| Get-MgBetaDeviceManagementMacOSSoftwareUpdateAccountSummaryCategorySummaryUpdateStateSummary | Minor changes |
| Get-MgBetaDeviceManagementManagedDeviceCleanupRule | Minor changes |
| Get-MgBetaDeviceManagementManagedDeviceHealthScriptState | Minor changes |
| Get-MgBetaDeviceManagementManagedDeviceLogCollectionRequest | Minor changes |
| Get-MgBetaDeviceManagementManagedDeviceSecurityBaselineStateSettingState | Minor changes |
| Get-MgBetaDeviceManagementManagedDeviceWindowsProtectionStateDetectedMalwareState | Minor changes |
| Get-MgBetaDeviceManagementMicrosoftTunnelConfiguration | Minor changes |
| Get-MgBetaDeviceManagementMicrosoftTunnelHealthThreshold | Minor changes |
| Get-MgBetaDeviceManagementMonitoringAlertRule | Minor changes |
| Get-MgBetaDeviceManagementNotificationMessageTemplate | Minor changes |
| Get-MgBetaDeviceManagementReportActiveMalwareReport | Minor changes |
| Get-MgBetaDeviceManagementReportActiveMalwareSummaryReport | Minor changes |
| Get-MgBetaDeviceManagementReportAppInstallSummaryReport | Minor changes |
| Get-MgBetaDeviceManagementReportAppStatusOverviewReport | Minor changes |
| Get-MgBetaDeviceManagementReportCachedReport | Minor changes |
| Get-MgBetaDeviceManagementReportCompliancePolicyDeviceReport | Minor changes |
| Get-MgBetaDeviceManagementReportCompliancePolicyDeviceSummaryReport | Minor changes |
| Get-MgBetaDeviceManagementReportCompliancePolicyNonComplianceReport | Minor changes |
| Get-MgBetaDeviceManagementReportCompliancePolicyNonComplianceSummaryReport | Minor changes |
| Get-MgBetaDeviceManagementReportCompliancePolicyReportForDevice | Minor changes |
| Get-MgBetaDeviceManagementReportComplianceSettingDetailReport | Minor changes |
| Get-MgBetaDeviceManagementReportComplianceSettingNonComplianceReport | Minor changes |
| Get-MgBetaDeviceManagementReportComplianceSettingReport | Minor changes |
| Get-MgBetaDeviceManagementReportConfigManagerDevicePolicyStatusReport | Minor changes |
| Get-MgBetaDeviceManagementReportConfigurationPolicyDeviceReport | Minor changes |
| Get-MgBetaDeviceManagementReportConfigurationPolicyDeviceSummaryReport | Minor changes |
| Get-MgBetaDeviceManagementReportConfigurationPolicyNonComplianceReport | Minor changes |
| Get-MgBetaDeviceManagementReportConfigurationPolicyNonComplianceSummaryReport | Minor changes |
| Get-MgBetaDeviceManagementReportConfigurationPolicyReportForDevice | Minor changes |
| Get-MgBetaDeviceManagementReportConfigurationPolicySettingDeviceSummaryReport | Minor changes |
| Get-MgBetaDeviceManagementReportConfigurationSettingDetailReport | Minor changes |
| Get-MgBetaDeviceManagementReportConfigurationSettingNonComplianceReport | Minor changes |
| Get-MgBetaDeviceManagementReportConfigurationSettingReport | Minor changes |
| Get-MgBetaDeviceManagementReportDeviceConfigurationPolicySettingSummaryReport | Minor changes |
| Get-MgBetaDeviceManagementReportDeviceConfigurationPolicyStatusSummary | Minor changes |
| Get-MgBetaDeviceManagementReportDeviceInstallStatusReport | Minor changes |
| Get-MgBetaDeviceManagementReportDeviceManagementIntentPerSettingContributingProfile | Minor changes |
| Get-MgBetaDeviceManagementReportDeviceManagementIntentSettingReport | Minor changes |
| Get-MgBetaDeviceManagementReportDeviceNonComplianceReport | Minor changes |
| Get-MgBetaDeviceManagementReportDevicePolicyComplianceReport | Minor changes |
| Get-MgBetaDeviceManagementReportDevicePolicySettingComplianceReport | Minor changes |
| Get-MgBetaDeviceManagementReportDeviceStatusByCompliacePolicyReport | Minor changes |
| Get-MgBetaDeviceManagementReportDeviceStatusByCompliancePolicySettingReport | Minor changes |
| Get-MgBetaDeviceManagementReportDeviceStatusByPolicyPlatformComplianceReport | Minor changes |
| Get-MgBetaDeviceManagementReportDeviceStatusBySettingReport | Minor changes |
| Get-MgBetaDeviceManagementReportDeviceStatusSummaryByCompliacePolicyReport | Minor changes |
| Get-MgBetaDeviceManagementReportDeviceStatusSummaryByCompliancePolicySettingReport | Minor changes |
| Get-MgBetaDeviceManagementReportDeviceWithoutCompliancePolicyReport | Minor changes |
| Get-MgBetaDeviceManagementReportEncryptionReportForDevice | Minor changes |
| Get-MgBetaDeviceManagementReportEnrollmentConfigurationPolicyByDevice | Minor changes |
| Get-MgBetaDeviceManagementReportExportJob | Minor changes |
| Get-MgBetaDeviceManagementReportFailedMobileAppReport | Minor changes |
| Get-MgBetaDeviceManagementReportFailedMobileAppSummaryReport | Minor changes |
| Get-MgBetaDeviceManagementReportFilter | Minor changes |
| Get-MgBetaDeviceManagementReportGroupPolicySettingDeviceSettingReport | Minor changes |
| Get-MgBetaDeviceManagementReportHistoricalReport | Minor changes |
| Get-MgBetaDeviceManagementReportMalwareSummaryReport | Minor changes |
| Get-MgBetaDeviceManagementReportMobileApplicationManagementAppConfigurationReport | Minor changes |
| Get-MgBetaDeviceManagementReportMobileApplicationManagementAppRegistrationSummaryReport | Minor changes |
| Get-MgBetaDeviceManagementReportNoncompliantDeviceAndSettingReport | Minor changes |
| Get-MgBetaDeviceManagementReportPolicyNonComplianceMetadata | Minor changes |
| Get-MgBetaDeviceManagementReportPolicyNonComplianceReport | Minor changes |
| Get-MgBetaDeviceManagementReportPolicyNonComplianceSummaryReport | Minor changes |
| Get-MgBetaDeviceManagementReportQuietTimePolicyUserReport | Minor changes |
| Get-MgBetaDeviceManagementReportQuietTimePolicyUserSummaryReport | Minor changes |
| Get-MgBetaDeviceManagementReportRelatedAppStatusReport | Minor changes |
| Get-MgBetaDeviceManagementReportRemoteAssistanceSessionReport | Minor changes |
| Get-MgBetaDeviceManagementReportSettingNonComplianceReport | Minor changes |
| Get-MgBetaDeviceManagementReportUnhealthyDefenderAgentReport | Minor changes |
| Get-MgBetaDeviceManagementReportUnhealthyFirewallReport | Minor changes |
| Get-MgBetaDeviceManagementReportUnhealthyFirewallSummaryReport | Minor changes |
| Get-MgBetaDeviceManagementReportUserInstallStatusReport | Minor changes |
| Get-MgBetaDeviceManagementReportWin32CatalogAppUpdateReport | Minor changes |
| Get-MgBetaDeviceManagementReportWindowsDriverUpdateAlertPerPolicyPerDeviceReport | Minor changes |
| Get-MgBetaDeviceManagementReportWindowsDriverUpdateAlertSummaryReport | Minor changes |
| Get-MgBetaDeviceManagementReportWindowsQualityUpdateAlertPerPolicyPerDeviceReport | Minor changes |
| Get-MgBetaDeviceManagementReportWindowsQualityUpdateAlertSummaryReport | Minor changes |
| Get-MgBetaDeviceManagementReportWindowsUpdateAlertPerPolicyPerDeviceReport | Minor changes |
| Get-MgBetaDeviceManagementReportWindowsUpdateAlertSummaryReport | Minor changes |
| Get-MgBetaDeviceManagementReportZebraFotaDeploymentReport | Minor changes |
| Get-MgBetaDeviceManagementRoleAssignmentRoleScopeTag | Minor changes |
| Get-MgBetaDeviceManagementRoleScopeTag | Minor changes |
| Get-MgBetaDeviceManagementRoleScopeTagAssignment | Minor changes |
| Get-MgBetaDeviceManagementScriptAssignment | Minor changes |
| Get-MgBetaDeviceManagementTelecomExpenseManagementPartner | Minor changes |
| Get-MgBetaDeviceManagementTemplateCategoryRecommendedSetting | Minor changes |
| Get-MgBetaDeviceManagementTemplateCategorySettingDefinition | Minor changes |
| Get-MgBetaDeviceManagementTemplateMigratableToCategorySettingDefinition | Minor changes |
| Get-MgBetaDeviceManagementTermAndCondition | Minor changes |
| Get-MgBetaDeviceManagementTermAndConditionAcceptanceStatus | Minor changes |
| Get-MgBetaDeviceManagementUserExperienceAnalyticAppHealthApplicationPerformance | Minor changes |
| Get-MgBetaDeviceManagementUserExperienceAnalyticAppHealthApplicationPerformanceByAppVersionDetail | Minor changes |
| Get-MgBetaDeviceManagementUserExperienceAnalyticAppHealthApplicationPerformanceByAppVersionDeviceId | Minor changes |
| Get-MgBetaDeviceManagementUserExperienceAnalyticAppHealthDeviceModelPerformance | Minor changes |
| Get-MgBetaDeviceManagementUserExperienceAnalyticAppHealthDevicePerformance | Minor changes |
| Get-MgBetaDeviceManagementUserExperienceAnalyticAppHealthDevicePerformanceDetail | Minor changes |
| Get-MgBetaDeviceManagementUserExperienceAnalyticAppHealthOSVersionPerformance | Minor changes |
| Get-MgBetaDeviceManagementUserExperienceAnalyticAppHealthOverviewMetricValue | Minor changes |
| Get-MgBetaDeviceManagementUserExperienceAnalyticBatteryHealthDeviceAppImpact | Minor changes |
| Get-MgBetaDeviceManagementUserExperienceAnalyticBatteryHealthOSPerformance | Minor changes |
| Get-MgBetaDeviceManagementUserExperienceAnalyticCategoryMetricValue | Minor changes |
| Get-MgBetaDeviceManagementUserExperienceAnalyticDeviceMetricHistory | Minor changes |
| Get-MgBetaDeviceManagementUserExperienceAnalyticDeviceScope | Minor changes |
| Get-MgBetaDeviceManagementUserExperienceAnalyticImpactingProcess | Minor changes |
| Get-MgBetaDeviceManagementUserExperienceAnalyticNotAutopilotReadyDevice | Minor changes |
| Get-MgBetaDeviceManagementUserExperienceAnalyticRemoteConnection | Minor changes |
| Get-MgBetaDeviceManagementUserExperienceAnalyticScoreHistory | Minor changes |
| Get-MgBetaDeviceManagementUserExperienceAnalyticWorkFromAnywhereMetric | Minor changes |
| Get-MgBetaDeviceManagementUserPfxCertificate | Minor changes |
| Get-MgBetaDeviceManagementVirtualEndpointAuditEvent | Minor changes |
| Get-MgBetaDeviceManagementVirtualEndpointBulkAction | Minor changes |
| Get-MgBetaDeviceManagementVirtualEndpointCloudPc | Minor changes |
| Get-MgBetaDeviceManagementVirtualEndpointGalleryImage | Minor changes |
| Get-MgBetaDeviceManagementVirtualEndpointProvisioningPolicyAssignment | Minor changes |
| Get-MgBetaDeviceManagementVirtualEndpointProvisioningPolicyAssignmentAssignedUser | Minor changes |
| Get-MgBetaDeviceManagementVirtualEndpointSnapshot | Minor changes |
| Get-MgBetaDeviceManagementVirtualEndpointUserSetting | Minor changes |
| Get-MgBetaDeviceManagementVirtualEndpointUserSettingAssignment | Minor changes |
| Get-MgBetaDeviceManagementWindowsAutopilotDeploymentProfileAssignment | Minor changes |
| Get-MgBetaDeviceManagementWindowsAutopilotDeviceIdentity | Minor changes |
| Get-MgBetaDeviceManagementWindowsFeatureUpdateProfile | Minor changes |
| Get-MgBetaDeviceManagementWindowsInformationProtectionAppLearningSummary | Minor changes |
| Get-MgBetaDeviceManagementWindowsInformationProtectionNetworkLearningSummary | Minor changes |
| Get-MgBetaDeviceMemberOf | Minor changes |
| Get-MgBetaDeviceRegisteredOwnerAsEndpoint | Minor changes |
| Get-MgBetaDeviceRegisteredOwnerAsServicePrincipal | Minor changes |
| Get-MgBetaDeviceRegisteredOwnerAsUser | Minor changes |
| Get-MgBetaDeviceRegisteredUserAsEndpoint | Minor changes |
| Get-MgBetaDeviceRegisteredUserAsUser | Minor changes |
| Get-MgBetaDeviceTransitiveMemberOfAsGroup | Minor changes |
| Get-MgBetaDeviceUsageRights | Minor changes |
| Get-MgBetaDirectoryAdministrativeUnitMemberAsDevice | Minor changes |
| Get-MgBetaDirectoryAdministrativeUnitMemberAsUser | Minor changes |
| Get-MgBetaDirectoryCertificateAuthorityCertificateBasedApplicationConfiguration | Minor changes |
| Get-MgBetaDirectoryCertificateAuthorityCertificateBasedApplicationConfigurationCount | Minor changes |
| Get-MgBetaDirectoryCertificateAuthorityCertificateBasedApplicationConfigurationTrustedCertificateAuthority | Minor changes |
| Get-MgBetaDirectoryCertificateAuthorityCertificateBasedApplicationConfigurationTrustedCertificateAuthorityCount | Minor changes |
| Get-MgBetaDirectoryDeletedItemAsAdministrativeUnit | Minor changes |
| Get-MgBetaDirectoryDeletedItemAsDevice | Minor changes |
| Get-MgBetaDirectoryDeletedItemAsServicePrincipal | Minor changes |
| Get-MgBetaDirectoryExternalUserProfile | Minor changes |
| Get-MgBetaDirectoryExternalUserProfileCount | Minor changes |
| Get-MgBetaDirectoryFederationConfiguration | Minor changes |
| Get-MgBetaDirectoryOnPremiseSynchronization | Minor changes |
| Get-MgBetaDirectoryOutboundSharedUserProfile | Minor changes |
| Get-MgBetaDirectoryOutboundSharedUserProfileTenant | Minor changes |
| Get-MgBetaDirectoryPendingExternalUserProfile | Minor changes |
| Get-MgBetaDirectoryPendingExternalUserProfileCount | Minor changes |
| Get-MgBetaDirectoryRole | Minor changes |
| Get-MgBetaDirectoryRoleMemberAsOrgContact | Minor changes |
| Get-MgBetaDirectoryRoleTemplate | Minor changes |
| Get-MgBetaDirectorySetting | Minor changes |
| Get-MgBetaDomain | Minor changes |
| Get-MgBetaDomainFederationConfiguration | Minor changes |
| Get-MgBetaDomainServiceConfigurationRecord | Minor changes |
| Get-MgBetaDomainSharedEmailDomainInvitation | Minor changes |
| Get-MgBetaDrive | Minor changes |
| Get-MgBetaDriveBundle | Minor changes |
| Get-MgBetaDriveItemThumbnail | Minor changes |
| Get-MgBetaDriveListColumn | Minor changes |
| Get-MgBetaDriveListContentType | Minor changes |
| Get-MgBetaDriveListContentTypeColumn | Minor changes |
| Get-MgBetaDriveListContentTypeColumnPosition | Minor changes |
| Get-MgBetaDriveListItem | Minor changes |
| Get-MgBetaDriveListItemDocumentSetVersion | Minor changes |
| Get-MgBetaDriveListItemVersion | Minor changes |
| Get-MgBetaDriveListOperation | Minor changes |
| Get-MgBetaDriveRootAnalyticItemActivityStat | Minor changes |
| Get-MgBetaDriveRootListItemDocumentSetVersion | Minor changes |
| Get-MgBetaDriveRootListItemPermission | Minor changes |
| Get-MgBetaDriveRootListItemVersion | Minor changes |
| Get-MgBetaDriveRootPermission | Minor changes |
| Get-MgBetaDriveRootThumbnail | Minor changes |
| Get-MgBetaDriveSpecial | Minor changes |
| Get-MgBetaEducationClassAssignmentResource | Minor changes |
| Get-MgBetaEducationClassAssignmentSettingGradingCategory | Minor changes |
| Get-MgBetaEducationClassAssignmentSubmissionOutcome | Minor changes |
| Get-MgBetaEducationClassModuleResource | Minor changes |
| Get-MgBetaEducationMeAssignment | Minor changes |
| Get-MgBetaEducationMeAssignmentResource | Minor changes |
| Get-MgBetaEducationMeAssignmentResourceDependentResource | Minor changes |
| Get-MgBetaEducationMeAssignmentSubmission | Minor changes |
| Get-MgBetaEducationMeAssignmentSubmissionResourceDependentResource | Minor changes |
| Get-MgBetaEducationMeRubric | Minor changes |
| Get-MgBetaEducationSchool | Minor changes |
| Get-MgBetaEducationSynchronizationProfile | Minor changes |
| Get-MgBetaEducationSynchronizationProfileCount | Minor changes |
| Get-MgBetaEducationSynchronizationProfileError | Minor changes |
| Get-MgBetaEducationSynchronizationProfileErrorCount | Minor changes |
| Get-MgBetaEducationSynchronizationProfileStatus | Minor changes |
| Get-MgBetaEducationUserAssignmentResourceDependentResource | Minor changes |
| Get-MgBetaEducationUserAssignmentSubmissionResource | Minor changes |
| Get-MgBetaEducationUserAssignmentSubmissionResourceDependentResource | Minor changes |
| Get-MgBetaEntitlementManagementAccessPackageAssignmentPolicyCustomExtensionHandler | Minor changes |
| Get-MgBetaEntitlementManagementAccessPackageAssignmentResourceRole | Minor changes |
| Get-MgBetaEntitlementManagementAccessPackageCatalog | Minor changes |
| Get-MgBetaEntitlementManagementAccessPackageCatalogCustomAccessPackageWorkflowExtension | Minor changes |
| Get-MgBetaEntitlementManagementAccessPackageIncompatibleWith | Minor changes |
| Get-MgBetaEntitlementManagementAccessPackageResourceEnvironment | Minor changes |
| Get-MgBetaEntitlementManagementAssignmentRequest | Minor changes |
| Get-MgBetaExternalConnectionGroup | Minor changes |
| Get-MgBetaExternalConnectionGroupMember | Minor changes |
| Get-MgBetaExternalIndustryDataInboundFlow | Minor changes |
| Get-MgBetaExternalIndustryDataOutboundProvisioningFlowSet | Minor changes |
| Get-MgBetaExternalIndustryDataOutboundProvisioningFlowSetCount | Minor changes |
| Get-MgBetaExternalIndustryDataOutboundProvisioningFlowSetProvisioningFlow | Minor changes |
| Get-MgBetaExternalIndustryDataReferenceDefinition | Minor changes |
| Get-MgBetaExternalIndustryDataRun | Minor changes |
| Get-MgBetaExternalIndustryDataRunActivity | Minor changes |
| Get-MgBetaFinancialCompany | Minor changes |
| Get-MgBetaFinancialCompanyCountryRegion | Minor changes |
| Get-MgBetaFinancialCompanyCustomerPayment | Minor changes |
| Get-MgBetaFinancialCompanyCustomerPaymentJournal | Minor changes |
| Get-MgBetaFinancialCompanyCustomerPaymentJournalCustomerPayment | Minor changes |
| Get-MgBetaFinancialCompanyDimensionValue | Minor changes |
| Get-MgBetaFinancialCompanyEmployee | Minor changes |
| Get-MgBetaFinancialCompanyGeneralLedgerEntry | Minor changes |
| Get-MgBetaFinancialCompanyItemCategory | Minor changes |
| Get-MgBetaFinancialCompanyItemPicture | Minor changes |
| Get-MgBetaFinancialCompanyPaymentMethod | Minor changes |
| Get-MgBetaFinancialCompanyPaymentTerm | Minor changes |
| Get-MgBetaFinancialCompanyPurchaseInvoice | Minor changes |
| Get-MgBetaFinancialCompanyPurchaseInvoiceLineItemPicture | Minor changes |
| Get-MgBetaFinancialCompanySaleCreditMemoLine | Minor changes |
| Get-MgBetaFinancialCompanySaleCreditMemoSaleCreditMemoLine | Minor changes |
| Get-MgBetaFinancialCompanySaleCreditMemoSaleCreditMemoLineItemPicture | Minor changes |
| Get-MgBetaFinancialCompanySaleInvoiceLine | Minor changes |
| Get-MgBetaFinancialCompanySaleOrderLine | Minor changes |
| Get-MgBetaFinancialCompanySaleQuote | Minor changes |
| Get-MgBetaFinancialCompanySaleQuoteLine | Minor changes |
| Get-MgBetaFinancialCompanyVendor | Minor changes |
| Get-MgBetaGroupCalendarEvent | Minor changes |
| Get-MgBetaGroupCalendarPermission | Minor changes |
| Get-MgBetaGroupCalendarSchedule | Minor changes |
| Get-MgBetaGroupConversation | Minor changes |
| Get-MgBetaGroupConversationThread | Minor changes |
| Get-MgBetaGroupConversationThreadPostExtension | Minor changes |
| Get-MgBetaGroupConversationThreadPostMention | Minor changes |
| Get-MgBetaGroupDriveContentTypeBaseType | Minor changes |
| Get-MgBetaGroupDriveItem | Minor changes |
| Get-MgBetaGroupDriveItemActivityByInterval | Minor changes |
| Get-MgBetaGroupDriveItemAnalyticItemActivityStat | Minor changes |
| Get-MgBetaGroupDriveItemDelta | Minor changes |
| Get-MgBetaGroupDriveItemListItemActivityByInterval | Minor changes |
| Get-MgBetaGroupDriveItemListItemDocumentSetVersion | Minor changes |
| Get-MgBetaGroupDriveItemPermission | Minor changes |
| Get-MgBetaGroupDriveItemSubscription | Minor changes |
| Get-MgBetaGroupDriveItemThumbnail | Minor changes |
| Get-MgBetaGroupDriveListColumn | Minor changes |
| Get-MgBetaGroupDriveListContentTypeColumnLink | Minor changes |
| Get-MgBetaGroupDriveListContentTypeColumnPosition | Minor changes |
| Get-MgBetaGroupDriveListContentTypeCompatibleHubContentType | Minor changes |
| Get-MgBetaGroupDriveListItem | Minor changes |
| Get-MgBetaGroupDriveListItemActivityByInterval | Minor changes |
| Get-MgBetaGroupDriveListItemDelta | Minor changes |
| Get-MgBetaGroupDriveListItemPermission | Minor changes |
| Get-MgBetaGroupDriveListItemVersion | Minor changes |
| Get-MgBetaGroupDriveRootActivityByInterval | Minor changes |
| Get-MgBetaGroupDriveRootDelta | Minor changes |
| Get-MgBetaGroupDriveRootListItemActivityByInterval | Minor changes |
| Get-MgBetaGroupDriveRootListItemPermission | Minor changes |
| Get-MgBetaGroupDriveRootPermission | Minor changes |
| Get-MgBetaGroupDriveRootThumbnail | Minor changes |
| Get-MgBetaGroupEndpoint | Minor changes |
| Get-MgBetaGroupEvent | Minor changes |
| Get-MgBetaGroupEventDelta | Minor changes |
| Get-MgBetaGroupMemberAsDevice | Minor changes |
| Get-MgBetaGroupMemberOfAsGroup | Minor changes |
| Get-MgBetaGroupMemberWithLicenseError | Minor changes |
| Get-MgBetaGroupMemberWithLicenseErrorAsServicePrincipal | Minor changes |
| Get-MgBetaGroupOnenoteNotebookFromWebUrl | Minor changes |
| Get-MgBetaGroupOnenoteNotebookSection | Minor changes |
| Get-MgBetaGroupOnenoteNotebookSectionGroup | Minor changes |
| Get-MgBetaGroupOnenoteSectionGroupSection | Minor changes |
| Get-MgBetaGroupOnenoteSectionPage | Minor changes |
| Get-MgBetaGroupOwnerAsApplication | Minor changes |
| Get-MgBetaGroupOwnerAsDevice | Minor changes |
| Get-MgBetaGroupOwnerAsOrgContact | Minor changes |
| Get-MgBetaGroupPermissionGrant | Minor changes |
| Get-MgBetaGroupPhoto | Minor changes |
| Get-MgBetaGroupPlannerPlanDelta | Minor changes |
| Get-MgBetaGroupSiteActivityByInterval | Minor changes |
| Get-MgBetaGroupSiteAnalyticItemActivityStatActivity | Minor changes |
| Get-MgBetaGroupSiteApplicableContentTypeForList | Minor changes |
| Get-MgBetaGroupSiteByPath | Minor changes |
| Get-MgBetaGroupSiteColumn | Minor changes |
| Get-MgBetaGroupSiteContentModel | Minor changes |
| Get-MgBetaGroupSiteContentModelAppliedDrive | Minor changes |
| Get-MgBetaGroupSiteContentModelByName | Minor changes |
| Get-MgBetaGroupSiteContentType | Minor changes |
| Get-MgBetaGroupSiteContentTypeBaseType | Minor changes |
| Get-MgBetaGroupSiteContentTypeColumn | Minor changes |
| Get-MgBetaGroupSiteContentTypeColumnLink | Minor changes |
| Get-MgBetaGroupSiteContentTypeCompatibleHubContentType | Minor changes |
| Get-MgBetaGroupSiteDelta | Minor changes |
| Get-MgBetaGroupSiteDrive | Minor changes |
| Get-MgBetaGroupSiteExternalColumn | Minor changes |
| Get-MgBetaGroupSiteGetByPathDrive | Minor changes |
| Get-MgBetaGroupSiteInformationProtectionDataLossPreventionPolicy | Minor changes |
| Get-MgBetaGroupSiteInformationProtectionSensitivityLabelSublabel | Minor changes |
| Get-MgBetaGroupSiteInformationProtectionThreatAssessmentRequest | Minor changes |
| Get-MgBetaGroupSiteList | Minor changes |
| Get-MgBetaGroupSiteListContentTypeColumn | Minor changes |
| Get-MgBetaGroupSiteListContentTypeColumnLink | Minor changes |
| Get-MgBetaGroupSiteListContentTypeCompatibleHubContentType | Minor changes |
| Get-MgBetaGroupSiteListItemActivityByInterval | Minor changes |
| Get-MgBetaGroupSiteListItemDelta | Minor changes |
| Get-MgBetaGroupSiteListOperation | Minor changes |
| Get-MgBetaGroupSiteListSubscription | Minor changes |
| Get-MgBetaGroupSiteOnenoteNotebookSection | Minor changes |
| Get-MgBetaGroupSiteOnenoteNotebookSectionGroup | Minor changes |
| Get-MgBetaGroupSiteOnenoteNotebookSectionGroupSection | Minor changes |
| Get-MgBetaGroupSiteOnenoteNotebookSectionPage | Minor changes |
| Get-MgBetaGroupSiteOnenotePage | Minor changes |
| Get-MgBetaGroupSiteOnenoteResource | Minor changes |
| Get-MgBetaGroupSiteOnenoteSection | Minor changes |
| Get-MgBetaGroupSitePageAsSitePageCanvaLayoutHorizontalSectionColumn | Minor changes |
| Get-MgBetaGroupSitePageAsSitePageCanvaLayoutHorizontalSectionColumnWebpart | Minor changes |
| Get-MgBetaGroupSitePageAsSitePageCanvaLayoutVerticalSectionWebpart | Minor changes |
| Get-MgBetaGroupSitePageMicrosoftGraphSitePageCanvaLayoutHorizontalSectionColumnWebpartPositionOfWebPart | Minor changes |
| Get-MgBetaGroupSitePageMicrosoftGraphSitePageCanvaLayoutVerticalSectionWebpartPositionOfWebPart | Minor changes |
| Get-MgBetaGroupSitePageMicrosoftGraphSitePageWebPartPositionOfWebPart | Minor changes |
| Get-MgBetaGroupSitePageTemplateCanvaLayoutHorizontalSectionColumn | Minor changes |
| Get-MgBetaGroupSitePageTemplateCanvaLayoutHorizontalSectionColumnWebpartPositionOfWebPart | Minor changes |
| Get-MgBetaGroupSitePageTemplateCanvaLayoutVerticalSectionWebpart | Minor changes |
| Get-MgBetaGroupSitePageTemplateCanvaLayoutVerticalSectionWebpartPositionOfWebPart | Minor changes |
| Get-MgBetaGroupSitePageTemplateWebPartPositionOfWebPart | Minor changes |
| Get-MgBetaGroupSitePermission | Minor changes |
| Get-MgBetaGroupSiteTermStoreGroupSetTerm | Minor changes |
| Get-MgBetaGroupSiteTermStoreSet | Minor changes |
| Get-MgBetaGroupSiteTermStoreSetParentGroupSet | Minor changes |
| Get-MgBetaGroupSiteTermStoreSetParentGroupSetTerm | Minor changes |
| Get-MgBetaGroupTeamChannel | Minor changes |
| Get-MgBetaGroupTeamChannelMember | Minor changes |
| Get-MgBetaGroupTeamChannelMessage | Minor changes |
| Get-MgBetaGroupTeamChannelMessageReply | Minor changes |
| Get-MgBetaGroupTeamChannelMessageReplyHostedContent | Minor changes |
| Get-MgBetaGroupTeamIncomingChannel | Minor changes |
| Get-MgBetaGroupTeamInstalledApp | Minor changes |
| Get-MgBetaGroupTeamOperation | Minor changes |
| Get-MgBetaGroupTeamOwner | Minor changes |
| Get-MgBetaGroupTeamPrimaryChannelMember | Minor changes |
| Get-MgBetaGroupTeamPrimaryChannelMessage | Minor changes |
| Get-MgBetaGroupTeamPrimaryChannelSharedWithTeam | Minor changes |
| Get-MgBetaGroupTeamScheduleDayNote | Minor changes |
| Get-MgBetaGroupTeamScheduleOfferShiftRequest | Minor changes |
| Get-MgBetaGroupTeamScheduleSchedulingGroup | Minor changes |
| Get-MgBetaGroupTeamScheduleShiftRoleDefinition | Minor changes |
| Get-MgBetaGroupTeamScheduleTimeCard | Minor changes |
| Get-MgBetaGroupTeamScheduleTimeOffReason | Minor changes |
| Get-MgBetaGroupTeamScheduleTimeOffRequest | Minor changes |
| Get-MgBetaGroupTeamTag | Minor changes |
| Get-MgBetaGroupThreadPost | Minor changes |
| Get-MgBetaGroupThreadPostExtension | Minor changes |
| Get-MgBetaGroupThreadPostMention | Minor changes |
| Get-MgBetaGroupTransitiveMember | Minor changes |
| Get-MgBetaGroupTransitiveMemberAsApplication | Minor changes |
| Get-MgBetaGroupTransitiveMemberAsDevice | Minor changes |
| Get-MgBetaGroupTransitiveMemberAsGroup | Minor changes |
| Get-MgBetaGroupTransitiveMemberAsServicePrincipal | Minor changes |
| Get-MgBetaGroupTransitiveMemberOf | Minor changes |
| Get-MgBetaGroupTransitiveMemberOfAsGroup | Minor changes |
| Get-MgBetaIdentityAuthenticationEventFlowAsExternalUserSelfServiceSignUpEventFlow | Minor changes |
| Get-MgBetaIdentityAuthenticationEventFlowAsExternalUserSelfServiceSignUpEventFlowIncludeApplication | Minor changes |
| Get-MgBetaIdentityAuthenticationEventFlowIncludeApplication | Minor changes |
| Get-MgBetaIdentityB2CUserFlowIdentityProvider | Minor changes |
| Get-MgBetaIdentityB2XUserFlow | Minor changes |
| Get-MgBetaIdentityB2XUserFlowIdentityProvider | Minor changes |
| Get-MgBetaIdentityB2XUserFlowLanguage | Minor changes |
| Get-MgBetaIdentityConditionalAccessAuthenticationContextClassReference | Minor changes |
| Get-MgBetaIdentityConditionalAccessAuthenticationStrengthPolicy | Minor changes |
| Get-MgBetaIdentityConditionalAccessAuthenticationStrengthPolicyCombinationConfiguration | Minor changes |
| Get-MgBetaIdentityGovernanceAccessReviewDecisionInstanceDecision | Minor changes |
| Get-MgBetaIdentityGovernanceAccessReviewDecisionInstanceStage | Minor changes |
| Get-MgBetaIdentityGovernanceAccessReviewDefinition | Minor changes |
| Get-MgBetaIdentityGovernanceAccessReviewDefinitionInstance | Minor changes |
| Get-MgBetaIdentityGovernanceAccessReviewDefinitionInstanceContactedReviewer | Minor changes |
| Get-MgBetaIdentityGovernanceAccessReviewDefinitionInstanceDecision | Minor changes |
| Get-MgBetaIdentityGovernanceAccessReviewDefinitionInstanceDecisionInsight | Minor changes |
| Get-MgBetaIdentityGovernanceAccessReviewDefinitionInstanceStage | Minor changes |
| Get-MgBetaIdentityGovernanceAccessReviewHistoryDefinitionInstance | Minor changes |
| Get-MgBetaIdentityGovernanceAppConsentRequest | Minor changes |
| Get-MgBetaIdentityGovernanceAppConsentRequestUserConsentRequestApprovalStep | Minor changes |
| Get-MgBetaIdentityGovernanceLifecycleWorkflowCustomTaskExtension | Minor changes |
| Get-MgBetaIdentityGovernanceLifecycleWorkflowDeletedItemWorkflow | Minor changes |
| Get-MgBetaIdentityGovernanceLifecycleWorkflowDeletedItemWorkflowExecutionScope | Minor changes |
| Get-MgBetaIdentityGovernanceLifecycleWorkflowDeletedItemWorkflowRun | Minor changes |
| Get-MgBetaIdentityGovernanceLifecycleWorkflowDeletedItemWorkflowTaskReport | Minor changes |
| Get-MgBetaIdentityGovernanceLifecycleWorkflowDeletedItemWorkflowUserProcessingResult | Minor changes |
| Get-MgBetaIdentityGovernanceLifecycleWorkflowDeletedItemWorkflowVersion | Minor changes |
| Get-MgBetaIdentityGovernanceLifecycleWorkflowExecutionScope | Minor changes |
| Get-MgBetaIdentityGovernanceLifecycleWorkflowRunTaskProcessingResult | Minor changes |
| Get-MgBetaIdentityGovernanceLifecycleWorkflowTask | Minor changes |
| Get-MgBetaIdentityGovernanceLifecycleWorkflowTaskDefinition | Minor changes |
| Get-MgBetaIdentityGovernanceLifecycleWorkflowTaskProcessingResult | Minor changes |
| Get-MgBetaIdentityGovernanceLifecycleWorkflowTaskReport | Minor changes |
| Get-MgBetaIdentityGovernanceLifecycleWorkflowTaskReportTaskProcessingResult | Minor changes |
| Get-MgBetaIdentityGovernanceLifecycleWorkflowUserProcessingResult | Minor changes |
| Get-MgBetaIdentityGovernanceLifecycleWorkflowUserProcessingResultTaskProcessingResult | Minor changes |
| Get-MgBetaIdentityGovernanceLifecycleWorkflowVersionTask | Minor changes |
| Get-MgBetaIdentityGovernancePermissionAnalyticAzureFinding | Minor changes |
| Get-MgBetaIdentityGovernancePermissionManagementPermissionRequestChange | Minor changes |
| Get-MgBetaIdentityGovernancePermissionManagementScheduledPermissionApproval | Minor changes |
| Get-MgBetaIdentityGovernancePermissionManagementScheduledPermissionApprovalStep | Minor changes |
| Get-MgBetaIdentityGovernancePrivilegedAccessGroupAssignmentScheduleInstance | Minor changes |
| Get-MgBetaIdentityGovernancePrivilegedAccessGroupEligibilityScheduleInstance | Minor changes |
| Get-MgBetaIdentityGovernancePrivilegedAccessGroupEligibilityScheduleRequest | Minor changes |
| Get-MgBetaIdentityGovernanceRoleManagementAlertIncident | Minor changes |
| Get-MgBetaIdentityGovernanceTermsOfUseAgreementFile | Minor changes |
| Get-MgBetaIdentityGovernanceTermsOfUseAgreementFileLocalizationVersion | Minor changes |
| Get-MgBetaIdentityProvider | Minor changes |
| Get-MgBetaIdentityUserFlowAttribute | Minor changes |
| Get-MgBetaInformationProtectionBitlockerRecoveryKey | Minor changes |
| Get-MgBetaInformationProtectionPolicyLabel | Minor changes |
| Get-MgBetaInformationProtectionThreatAssessmentRequestResult | Minor changes |
| Get-MgBetaNetworkAccessAlert | Minor changes |
| Get-MgBetaNetworkAccessAlertCount | Minor changes |
| Get-MgBetaNetworkAccessConnectivityBranch | Minor changes |
| Get-MgBetaNetworkAccessConnectivityBranchConnectivityConfiguration | Minor changes |
| Get-MgBetaNetworkAccessConnectivityBranchConnectivityConfigurationLink | Minor changes |
| Get-MgBetaNetworkAccessConnectivityBranchCount | Minor changes |
| Get-MgBetaNetworkAccessConnectivityBranchDeviceLink | Minor changes |
| Get-MgBetaNetworkAccessConnectivityBranchDeviceLinkCount | Minor changes |
| Get-MgBetaNetworkAccessConnectivityRemoteNetwork | Minor changes |
| Get-MgBetaNetworkAccessConnectivityRemoteNetworkDeviceLink | Minor changes |
| Get-MgBetaNetworkAccessFilteringPolicy | Minor changes |
| Get-MgBetaNetworkAccessFilteringPolicyCount | Minor changes |
| Get-MgBetaNetworkAccessFilteringPolicyRule | Minor changes |
| Get-MgBetaNetworkAccessFilteringPolicyRuleCount | Minor changes |
| Get-MgBetaNetworkAccessFilteringProfile | Minor changes |
| Get-MgBetaNetworkAccessFilteringProfileCount | Minor changes |
| Get-MgBetaNetworkAccessFilteringProfilePolicy | Minor changes |
| Get-MgBetaNetworkAccessFilteringProfilePolicyCount | Minor changes |
| Get-MgBetaNetworkAccessForwardingPolicy | Minor changes |
| Get-MgBetaNetworkAccessForwardingPolicyCount | Minor changes |
| Get-MgBetaNetworkAccessForwardingPolicyRule | Minor changes |
| Get-MgBetaNetworkAccessForwardingPolicyRuleCount | Minor changes |
| Get-MgBetaNetworkAccessForwardingProfile | Minor changes |
| Get-MgBetaNetworkAccessForwardingProfileCount | Minor changes |
| Get-MgBetaNetworkAccessForwardingProfilePolicy | Minor changes |
| Get-MgBetaNetworkAccessLogTraffic | Minor changes |
| Get-MgBetaNetworkAccessSettingConditionalAccess | Minor changes |
| Get-MgBetaNetworkAccessSettingCrossTenantAccess | Minor changes |
| Get-MgBetaNetworkAccessSettingEnrichedAuditLog | Minor changes |
| Get-MgBetaOnPremisePublishingProfile | Minor changes |
| Get-MgBetaOnPremisePublishingProfileAgentGroupAgent | Minor changes |
| Get-MgBetaOnPremisePublishingProfileApplicationSegment | Minor changes |
| Get-MgBetaOnPremisePublishingProfileConnector | Minor changes |
| Get-MgBetaOnPremisePublishingProfileConnectorGroup | Minor changes |
| Get-MgBetaOnPremisePublishingProfilePublishedResource | Minor changes |
| Get-MgBetaOrganization | Minor changes |
| Get-MgBetaOrganizationBrandingLocalization | Minor changes |
| Get-MgBetaOrganizationCount | Minor changes |
| Get-MgBetaPlaceAsRoom | Minor changes |
| Get-MgBetaPlaceAsRoomList | Minor changes |
| Get-MgBetaPlaceAsRoomListRoom | Minor changes |
| Get-MgBetaPolicyAppManagementPolicy | Minor changes |
| Get-MgBetaPolicyAuthenticationMethodPolicy | Minor changes |
| Get-MgBetaPolicyAuthenticationMethodPolicyAuthenticationMethodConfiguration | Minor changes |
| Get-MgBetaPolicyAuthenticationStrengthPolicy | Minor changes |
| Get-MgBetaPolicyAuthenticationStrengthPolicyCombinationConfiguration | Minor changes |
| Get-MgBetaPolicyClaimMappingPolicy | Minor changes |
| Get-MgBetaPolicyFeatureRolloutPolicy | Minor changes |
| Get-MgBetaPolicyFederatedTokenValidationPolicy | Minor changes |
| Get-MgBetaPolicyHomeRealmDiscoveryPolicy | Minor changes |
| Get-MgBetaPolicyHomeRealmDiscoveryPolicyApplyTo | Minor changes |
| Get-MgBetaPolicyPermissionGrantPolicy | Minor changes |
| Get-MgBetaPolicyPermissionGrantPolicyExclude | Minor changes |
| Get-MgBetaPolicyRoleManagementPolicyRule | Minor changes |
| Get-MgBetaPrintConnector | Minor changes |
| Get-MgBetaPrintPrinterJob | Minor changes |
| Get-MgBetaPrintService | Minor changes |
| Get-MgBetaPrintServiceCount | Minor changes |
| Get-MgBetaPrintServiceEndpoint | Minor changes |
| Get-MgBetaPrintServiceEndpointCount | Minor changes |
| Get-MgBetaPrivacySubjectRightsRequest | Minor changes |
| Get-MgBetaPrivacySubjectRightsRequestApprover | Minor changes |
| Get-MgBetaPrivacySubjectRightsRequestCollaborator | Minor changes |
| Get-MgBetaPrivacySubjectRightsRequestNote | Minor changes |
| Get-MgBetaPrivilegedAccess | Minor changes |
| Get-MgBetaPrivilegedAccessResourceRoleAssignment | Minor changes |
| Get-MgBetaPrivilegedAccessResourceRoleDefinition | Minor changes |
| Get-MgBetaPrivilegedAccessRoleAssignment | Minor changes |
| Get-MgBetaPrivilegedRole | Minor changes |
| Get-MgBetaPrivilegedRoleAssignmentRequest | Minor changes |
| Get-MgBetaPrivilegedRoleAssignmentRoleInfoAssignment | Minor changes |
| Get-MgBetaProgramControl | Minor changes |
| Get-MgBetaReportAppCredentialSignInActivity | Minor changes |
| Get-MgBetaReportApplicationSignInDetailedSummary | Minor changes |
| Get-MgBetaReportCredentialUserRegistrationDetail | Minor changes |
| Get-MgBetaReportMonthlyPrintUsageByPrinter | Minor changes |
| Get-MgBetaReportMonthlyPrintUsageSummaryByPrinter | Minor changes |
| Get-MgBetaReportServicePrincipalSignInActivity | Minor changes |
| Get-MgBetaReportUserCredentialUsageDetail | Minor changes |
| Get-MgBetaReportUserInsightDailyInactiveUser | Minor changes |
| Get-MgBetaReportUserInsightDailyInactiveUserByApplication | Minor changes |
| Get-MgBetaReportUserInsightMonthlyInactiveUserByApplication | Minor changes |
| Get-MgBetaReportUserInsightMonthlyMfaCompletion | Minor changes |
| Get-MgBetaRiskyServicePrincipalHistory | Minor changes |
| Get-MgBetaRiskyUser | Minor changes |
| Get-MgBetaRoleManagementCloudPcRoleAssignment | Minor changes |
| Get-MgBetaRoleManagementCloudPcRoleDefinition | Minor changes |
| Get-MgBetaRoleManagementCloudPcRoleDefinitionInheritPermissionFrom | Minor changes |
| Get-MgBetaRoleManagementDefenderResourceNamespace | Minor changes |
| Get-MgBetaRoleManagementDefenderRoleAssignmentAppScope | Minor changes |
| Get-MgBetaRoleManagementDefenderRoleAssignmentDirectoryScope | Minor changes |
| Get-MgBetaRoleManagementDefenderRoleDefinitionInheritPermissionFrom | Minor changes |
| Get-MgBetaRoleManagementDeviceManagementResourceNamespace | Minor changes |
| Get-MgBetaRoleManagementDeviceManagementResourceNamespaceResourceAction | Minor changes |
| Get-MgBetaRoleManagementDeviceManagementRoleAssignment | Minor changes |
| Get-MgBetaRoleManagementDeviceManagementRoleAssignmentDirectoryScope | Minor changes |
| Get-MgBetaRoleManagementDeviceManagementRoleAssignmentPrincipal | Minor changes |
| Get-MgBetaRoleManagementDirectoryResourceNamespace | Minor changes |
| Get-MgBetaRoleManagementDirectoryRoleAssignment | Minor changes |
| Get-MgBetaRoleManagementDirectoryRoleAssignmentSchedule | Minor changes |
| Get-MgBetaRoleManagementDirectoryRoleAssignmentScheduleRequest | Minor changes |
| Get-MgBetaRoleManagementDirectoryRoleEligibilitySchedule | Minor changes |
| Get-MgBetaRoleManagementDirectoryTransitiveRoleAssignment | Minor changes |
| Get-MgBetaRoleManagementEnterpriseApp | Minor changes |
| Get-MgBetaRoleManagementEnterpriseAppResourceNamespace | Minor changes |
| Get-MgBetaRoleManagementEnterpriseAppResourceNamespaceResourceAction | Minor changes |
| Get-MgBetaRoleManagementEnterpriseAppRoleAssignment | Minor changes |
| Get-MgBetaRoleManagementEnterpriseAppRoleAssignmentSchedule | Minor changes |
| Get-MgBetaRoleManagementEnterpriseAppRoleAssignmentScheduleRequest | Minor changes |
| Get-MgBetaRoleManagementEnterpriseAppRoleDefinition | Minor changes |
| Get-MgBetaRoleManagementEnterpriseAppRoleEligibilitySchedule | Minor changes |
| Get-MgBetaRoleManagementEntitlementManagementResourceNamespace | Minor changes |
| Get-MgBetaRoleManagementEntitlementManagementRoleAssignmentScheduleInstance | Minor changes |
| Get-MgBetaRoleManagementEntitlementManagementRoleDefinition | Minor changes |
| Get-MgBetaRoleManagementEntitlementManagementRoleDefinitionInheritPermissionFrom | Minor changes |
| Get-MgBetaRoleManagementEntitlementManagementRoleEligibilitySchedule | Minor changes |
| Get-MgBetaRoleManagementEntitlementManagementTransitiveRoleAssignment | Minor changes |
| Get-MgBetaRoleManagementExchangeCustomAppScope | Minor changes |
| Get-MgBetaRoleManagementExchangeResourceNamespaceResourceAction | Minor changes |
| Get-MgBetaRoleManagementExchangeRoleDefinition | Minor changes |
| Get-MgBetaSchemaExtension | Minor changes |
| Get-MgBetaSearchBookmark | Minor changes |
| Get-MgBetaSecurityAlert | Minor changes |
| Get-MgBetaSecurityAttackSimulation | Minor changes |
| Get-MgBetaSecurityAttackSimulationAutomationRun | Minor changes |
| Get-MgBetaSecurityAttackSimulationEndUserNotification | Minor changes |
| Get-MgBetaSecurityAttackSimulationEndUserNotificationDetail | Minor changes |
| Get-MgBetaSecurityAttackSimulationLoginPage | Minor changes |
| Get-MgBetaSecurityAttackSimulationPayload | Minor changes |
| Get-MgBetaSecurityAttackSimulationTraining | Minor changes |
| Get-MgBetaSecurityAttackSimulationTrainingLanguageDetail | Minor changes |
| Get-MgBetaSecurityCaseEdiscoveryCase | Minor changes |
| Get-MgBetaSecurityCaseEdiscoveryCaseCustodian | Minor changes |
| Get-MgBetaSecurityCaseEdiscoveryCaseCustodianUserSource | Minor changes |
| Get-MgBetaSecurityCaseEdiscoveryCaseLegalHoldSiteSource | Minor changes |
| Get-MgBetaSecurityCaseEdiscoveryCaseLegalHoldUserSource | Minor changes |
| Get-MgBetaSecurityCaseEdiscoveryCaseReviewSetFile | Minor changes |
| Get-MgBetaSecurityCaseEdiscoveryCaseReviewSetQuery | Minor changes |
| Get-MgBetaSecurityCaseEdiscoveryCaseSearch | Minor changes |
| Get-MgBetaSecurityCaseEdiscoveryCaseSearchCustodianSource | Minor changes |
| Get-MgBetaSecurityCaseEdiscoveryCaseSearchNoncustodialSource | Minor changes |
| Get-MgBetaSecurityCaseEdiscoveryCaseTagChildTag | Minor changes |
| Get-MgBetaSecurityCollaborationAnalyzedEmail | Minor changes |
| Get-MgBetaSecurityDomainSecurityProfile | Minor changes |
| Get-MgBetaSecurityFileSecurityProfile | Minor changes |
| Get-MgBetaSecurityHostSecurityProfile | Minor changes |
| Get-MgBetaSecurityIPSecurityProfile | Minor changes |
| Get-MgBetaSecurityIdentityHealthIssue | Minor changes |
| Get-MgBetaSecurityIdentitySensor | Minor changes |
| Get-MgBetaSecurityIncident | Minor changes |
| Get-MgBetaSecurityIncidentAlert | Minor changes |
| Get-MgBetaSecurityInformationProtectionSensitivityLabel | Minor changes |
| Get-MgBetaSecurityLabelCategorySubcategory | Minor changes |
| Get-MgBetaSecurityLabelCitation | Minor changes |
| Get-MgBetaSecurityLabelDepartment | Minor changes |
| Get-MgBetaSecurityLabelRetentionLabel | Minor changes |
| Get-MgBetaSecurityLabelRetentionLabelDispositionReviewStage | Minor changes |
| Get-MgBetaSecurityPartnerSecurityAlert | Minor changes |
| Get-MgBetaSecurityPartnerSecurityScoreHistory | Minor changes |
| Get-MgBetaSecurityRuleDetectionRule | Minor changes |
| Get-MgBetaSecuritySecureScore | Minor changes |
| Get-MgBetaSecuritySubjectRightsRequest | Minor changes |
| Get-MgBetaSecuritySubjectRightsRequestApprover | Minor changes |
| Get-MgBetaSecuritySubjectRightsRequestCollaborator | Minor changes |
| Get-MgBetaSecuritySubjectRightsRequestNote | Minor changes |
| Get-MgBetaSecurityThreatIntelligenceArticle | Minor changes |
| Get-MgBetaSecurityThreatIntelligenceArticleIndicator | Minor changes |
| Get-MgBetaSecurityThreatIntelligenceHost | Minor changes |
| Get-MgBetaSecurityThreatIntelligenceHostCookie | Minor changes |
| Get-MgBetaSecurityThreatIntelligenceHostPair | Minor changes |
| Get-MgBetaSecurityThreatIntelligenceHostPassiveDnsReverse | Minor changes |
| Get-MgBetaSecurityThreatIntelligenceHostSslCertificate | Minor changes |
| Get-MgBetaSecurityThreatIntelligenceHostTracker | Minor changes |
| Get-MgBetaSecurityThreatIntelligenceIntelProfileIndicator | Minor changes |
| Get-MgBetaSecurityThreatIntelligencePassiveDnsRecord | Minor changes |
| Get-MgBetaSecurityThreatIntelligenceSslCertificate | Minor changes |
| Get-MgBetaSecurityThreatIntelligenceSslCertificateRelatedHost | Minor changes |
| Get-MgBetaSecurityThreatIntelligenceVulnerabilityArticle | Minor changes |
| Get-MgBetaSecurityThreatIntelligenceWhoisHistoryRecord | Minor changes |
| Get-MgBetaSecurityThreatSubmissionEmailThreat | Minor changes |
| Get-MgBetaSecurityThreatSubmissionEmailThreatSubmissionPolicy | Minor changes |
| Get-MgBetaSecurityTiIndicator | Minor changes |
| Get-MgBetaSecurityTriggerTypeRetentionEventType | Minor changes |
| Get-MgBetaSecurityUserSecurityProfile | Minor changes |
| Get-MgBetaServiceAnnouncementHealthOverviewIssue | Minor changes |
| Get-MgBetaServiceAnnouncementMessage | Minor changes |
| Get-MgBetaServiceAnnouncementMessageAttachment | Minor changes |
| Get-MgBetaServicePrincipal | Minor changes |
| Get-MgBetaServicePrincipalAppManagementPolicy | Minor changes |
| Get-MgBetaServicePrincipalAppRoleAssignedTo | Minor changes |
| Get-MgBetaServicePrincipalAppRoleAssignment | Minor changes |
| Get-MgBetaServicePrincipalMemberOf | Minor changes |
| Get-MgBetaServicePrincipalMemberOfAsAdministrativeUnit | Minor changes |
| Get-MgBetaServicePrincipalMemberOfAsDirectoryRole | Minor changes |
| Get-MgBetaServicePrincipalMemberOfAsGroup | Minor changes |
| Get-MgBetaServicePrincipalOauth2PermissionGrant | Minor changes |
| Get-MgBetaServicePrincipalOwnedObject | Minor changes |
| Get-MgBetaServicePrincipalOwnedObjectAsEndpoint | Minor changes |
| Get-MgBetaServicePrincipalOwnedObjectAsServicePrincipal | Minor changes |
| Get-MgBetaServicePrincipalOwnerAsServicePrincipal | Minor changes |
| Get-MgBetaServicePrincipalOwnerAsUser | Minor changes |
| Get-MgBetaServicePrincipalPermissionGrantPreApprovalPolicy | Minor changes |
| Get-MgBetaServicePrincipalRemoteDesktopSecurityConfigurationTargetDeviceGroup | Minor changes |
| Get-MgBetaServicePrincipalRiskDetection | Minor changes |
| Get-MgBetaServicePrincipalSynchronizationJob | Minor changes |
| Get-MgBetaServicePrincipalSynchronizationTemplateSchemaDirectory | Minor changes |
| Get-MgBetaServicePrincipalTokenIssuancePolicy | Minor changes |
| Get-MgBetaShareListColumn | Minor changes |
| Get-MgBetaShareListContentTypeColumn | Minor changes |
| Get-MgBetaShareListItem | Minor changes |
| Get-MgBetaShareListItemDocumentSetVersion | Minor changes |
| Get-MgBetaShareListItemPermission | Minor changes |
| Get-MgBetaShareListItemVersion | Minor changes |
| Get-MgBetaShareListOperation | Minor changes |
| Get-MgBetaShareSharedDriveItemSharedDriveItem | Minor changes |
| Get-MgBetaSite | Minor changes |
| Get-MgBetaSiteAnalyticItemActivityStatActivity | Minor changes |
| Get-MgBetaSiteColumn | Minor changes |
| Get-MgBetaSiteContentType | Minor changes |
| Get-MgBetaSiteContentTypeColumn | Minor changes |
| Get-MgBetaSiteContentTypeColumnLink | Minor changes |
| Get-MgBetaSiteDrive | Minor changes |
| Get-MgBetaSiteGetByPathDrive | Minor changes |
| Get-MgBetaSiteList | Minor changes |
| Get-MgBetaSiteListContentTypeColumnLink | Minor changes |
| Get-MgBetaSiteListItemPermission | Minor changes |
| Get-MgBetaSiteListSubscription | Minor changes |
| Get-MgBetaSiteOnenoteNotebook | Minor changes |
| Get-MgBetaSiteOnenoteNotebookFromWebUrl | Minor changes |
| Get-MgBetaSiteOnenoteNotebookSection | Minor changes |
| Get-MgBetaSiteOnenoteNotebookSectionGroup | Minor changes |
| Get-MgBetaSiteOnenoteOperation | Minor changes |
| Get-MgBetaSiteOnenotePage | Minor changes |
| Get-MgBetaSiteOnenoteResource | Minor changes |
| Get-MgBetaSiteOnenoteSectionGroup | Minor changes |
| Get-MgBetaSiteOnenoteSectionPage | Minor changes |
| Get-MgBetaSiteOperation | Minor changes |
| Get-MgBetaSitePageAsSitePageCanvaLayoutHorizontalSectionColumn | Minor changes |
| Get-MgBetaSitePageAsSitePageWebPart | Minor changes |
| Get-MgBetaSitePermission | Minor changes |
| Get-MgBetaSiteTermStoreGroupSetChildRelation | Minor changes |
| Get-MgBetaSiteTermStoreGroupSetRelation | Minor changes |
| Get-MgBetaSiteTermStoreGroupSetTerm | Minor changes |
| Get-MgBetaSiteTermStoreGroupSetTermChild | Minor changes |
| Get-MgBetaSiteTermStoreGroupSetTermChildRelation | Minor changes |
| Get-MgBetaSiteTermStoreSetChild | Minor changes |
| Get-MgBetaSiteTermStoreSetChildRelation | Minor changes |
| Get-MgBetaSiteTermStoreSetParentGroupSetChild | Minor changes |
| Get-MgBetaSiteTermStoreSetParentGroupSetRelation | Minor changes |
| Get-MgBetaSiteTermStoreSetParentGroupSetTermChild | Minor changes |
| Get-MgBetaSiteTermStoreSetParentGroupSetTermRelation | Minor changes |
| Get-MgBetaSolutionBackupRestoreExchangeProtectionPolicy | Minor changes |
| Get-MgBetaSolutionBackupRestoreExchangeProtectionPolicyMailboxInclusionRule | Minor changes |
| Get-MgBetaSolutionBackupRestoreExchangeProtectionPolicyMailboxProtectionUnit | Minor changes |
| Get-MgBetaSolutionBackupRestoreExchangeRestoreSession | Minor changes |
| Get-MgBetaSolutionBackupRestoreExchangeRestoreSessionMailboxRestoreArtifact | Minor changes |
| Get-MgBetaSolutionBackupRestoreMailboxInclusionRule | Minor changes |
| Get-MgBetaSolutionBackupRestoreMailboxProtectionUnit | Minor changes |
| Get-MgBetaSolutionBackupRestoreOneDriveForBusinessProtectionPolicy | Minor changes |
| Get-MgBetaSolutionBackupRestoreOneDriveForBusinessProtectionPolicyDriveInclusionRule | Minor changes |
| Get-MgBetaSolutionBackupRestoreOneDriveForBusinessProtectionPolicyDriveProtectionUnit | Minor changes |
| Get-MgBetaSolutionBackupRestoreOneDriveForBusinessRestoreSession | Minor changes |
| Get-MgBetaSolutionBackupRestoreOneDriveForBusinessRestoreSessionDriveRestoreArtifact | Minor changes |
| Get-MgBetaSolutionBackupRestorePoint | Minor changes |
| Get-MgBetaSolutionBackupRestoreProtectionUnit | Minor changes |
| Get-MgBetaSolutionBackupRestoreServiceApp | Minor changes |
| Get-MgBetaSolutionBackupRestoreSession | Minor changes |
| Get-MgBetaSolutionBackupRestoreSharePointProtectionPolicySiteInclusionRule | Minor changes |
| Get-MgBetaSolutionBackupRestoreSharePointProtectionPolicySiteProtectionUnit | Minor changes |
| Get-MgBetaSolutionBackupRestoreSharePointRestoreSession | Minor changes |
| Get-MgBetaSolutionBackupRestoreSharePointRestoreSessionSiteRestoreArtifact | Minor changes |
| Get-MgBetaSolutionBackupRestoreSiteProtectionUnit | Minor changes |
| Get-MgBetaSolutionBusinessScenarioPlannerPlanConfigurationLocalization | Minor changes |
| Get-MgBetaSubSite | Minor changes |
| Get-MgBetaSubscribedSku | Minor changes |
| Get-MgBetaSubscription | Minor changes |
| Get-MgBetaTeam | Minor changes |
| Get-MgBetaTeamChannel | Minor changes |
| Get-MgBetaTeamChannelMember | Minor changes |
| Get-MgBetaTeamChannelMessage | Minor changes |
| Get-MgBetaTeamChannelMessageReplyHostedContent | Minor changes |
| Get-MgBetaTeamChannelSharedWithTeam | Minor changes |
| Get-MgBetaTeamChannelTab | Minor changes |
| Get-MgBetaTeamIncomingChannel | Minor changes |
| Get-MgBetaTeamInstalledApp | Minor changes |
| Get-MgBetaTeamMember | Minor changes |
| Get-MgBetaTeamPermissionGrant | Minor changes |
| Get-MgBetaTeamPermissionGrantCount | Minor changes |
| Get-MgBetaTeamPrimaryChannelMember | Minor changes |
| Get-MgBetaTeamPrimaryChannelMessageHostedContent | Minor changes |
| Get-MgBetaTeamPrimaryChannelMessageReply | Minor changes |
| Get-MgBetaTeamScheduleOfferShiftRequest | Minor changes |
| Get-MgBetaTeamScheduleShift | Minor changes |
| Get-MgBetaTeamScheduleShiftRoleDefinition | Minor changes |
| Get-MgBetaTeamScheduleTimeCard | Minor changes |
| Get-MgBetaTeamScheduleTimeOffReason | Minor changes |
| Get-MgBetaTeamScheduleTimeOffRequest | Minor changes |
| Get-MgBetaTeamTagMember | Minor changes |
| Get-MgBetaTeamworkDeletedTeamChannel | Minor changes |
| Get-MgBetaTeamworkDeletedTeamChannelMember | Minor changes |
| Get-MgBetaTeamworkDeletedTeamChannelMessage | Minor changes |
| Get-MgBetaTeamworkDeletedTeamChannelMessageReplyHostedContent | Minor changes |
| Get-MgBetaTeamworkDeletedTeamChannelSharedWithTeam | Minor changes |
| Get-MgBetaTeamworkDeletedTeamChannelTab | Minor changes |
| Get-MgBetaTeamworkDevice | Minor changes |
| Get-MgBetaTeamworkTeamTemplate | Minor changes |
| Get-MgBetaTeamworkTeamTemplateDefinition | Minor changes |
| Get-MgBetaTeamworkWorkforceIntegration | Minor changes |
| Get-MgBetaTenantRelationshipDelegatedAdminCustomer | Minor changes |
| Get-MgBetaTenantRelationshipDelegatedAdminRelationshipAccessAssignment | Minor changes |
| Get-MgBetaTenantRelationshipDelegatedAdminRelationshipRequest | Minor changes |
| Get-MgBetaTenantRelationshipManagedTenant | Minor changes |
| Get-MgBetaTenantRelationshipManagedTenantAggregatedPolicyCompliance | Minor changes |
| Get-MgBetaTenantRelationshipManagedTenantAlert | Minor changes |
| Get-MgBetaTenantRelationshipManagedTenantAlertEmailNotification | Minor changes |
| Get-MgBetaTenantRelationshipManagedTenantAlertLog | Minor changes |
| Get-MgBetaTenantRelationshipManagedTenantAlertRule | Minor changes |
| Get-MgBetaTenantRelationshipManagedTenantAlertRuleAlert | Minor changes |
| Get-MgBetaTenantRelationshipManagedTenantApiNotification | Minor changes |
| Get-MgBetaTenantRelationshipManagedTenantAppPerformance | Minor changes |
| Get-MgBetaTenantRelationshipManagedTenantCloudPcConnection | Minor changes |
| Get-MgBetaTenantRelationshipManagedTenantCustomizedInformation | Minor changes |
| Get-MgBetaTenantRelationshipManagedTenantDetailedInformation | Minor changes |
| Get-MgBetaTenantRelationshipManagedTenantDeviceAppPerformance | Minor changes |
| Get-MgBetaTenantRelationshipManagedTenantDeviceCompliancePolicySettingStateSummary | Minor changes |
| Get-MgBetaTenantRelationshipManagedTenantEmailNotification | Minor changes |
| Get-MgBetaTenantRelationshipManagedTenantManagedDeviceCompliance | Minor changes |
| Get-MgBetaTenantRelationshipManagedTenantManagementAction | Minor changes |
| Get-MgBetaTenantRelationshipManagedTenantManagementActionTenantDeploymentStatus | Minor changes |
| Get-MgBetaTenantRelationshipManagedTenantManagementTemplateCollection | Minor changes |
| Get-MgBetaTenantRelationshipManagedTenantManagementTemplateCollectionManagementTemplate | Minor changes |
| Get-MgBetaTenantRelationshipManagedTenantManagementTemplateStep | Minor changes |
| Get-MgBetaTenantRelationshipManagedTenantManagementTemplateStepVersion | Minor changes |
| Get-MgBetaTenantRelationshipManagedTenantManagementTemplateStepVersionDeployment | Minor changes |
| Get-MgBetaTenantRelationshipManagedTenantMyRole | Minor changes |
| Get-MgBetaTenantRelationshipManagedTenantWindowsProtectionState | Minor changes |
| Get-MgBetaTenantRelationshipMultiTenantOrganizationTenant | Minor changes |
| Get-MgBetaTrustFrameworkPolicy | Minor changes |
| Get-MgBetaUserActivityHistoryItem | Minor changes |
| Get-MgBetaUserActivityStatistics | Minor changes |
| Get-MgBetaUserAppRoleAssignedResource | Minor changes |
| Get-MgBetaUserAppRoleAssignment | Minor changes |
| Get-MgBetaUserAuthenticationFido2Method | Minor changes |
| Get-MgBetaUserAuthenticationFido2MethodCount | Minor changes |
| Get-MgBetaUserAuthenticationMethod | Minor changes |
| Get-MgBetaUserAuthenticationMicrosoftAuthenticatorMethod | Minor changes |
| Get-MgBetaUserAuthenticationWindowsHelloForBusinessMethod | Minor changes |
| Get-MgBetaUserCalendarGroup | Minor changes |
| Get-MgBetaUserCalendarPermission | Minor changes |
| Get-MgBetaUserChatInstalledApp | Minor changes |
| Get-MgBetaUserChatMessage | Minor changes |
| Get-MgBetaUserChatMessageCount | Minor changes |
| Get-MgBetaUserChatMessageDelta | Minor changes |
| Get-MgBetaUserChatMessageHostedContent | Minor changes |
| Get-MgBetaUserChatMessageHostedContentCount | Minor changes |
| Get-MgBetaUserChatMessageReply | Minor changes |
| Get-MgBetaUserChatMessageReplyDelta | Minor changes |
| Get-MgBetaUserChatMessageReplyHostedContent | Minor changes |
| Get-MgBetaUserChatOperation | Minor changes |
| Get-MgBetaUserChatPinnedMessage | Minor changes |
| Get-MgBetaUserChatRetainedMessage | Minor changes |
| Get-MgBetaUserContactDelta | Minor changes |
| Get-MgBetaUserContactFolderChildFolder | Minor changes |
| Get-MgBetaUserContactFolderChildFolderContact | Minor changes |
| Get-MgBetaUserContactFolderChildFolderContactDelta | Minor changes |
| Get-MgBetaUserContactFolderChildFolderContactExtension | Minor changes |
| Get-MgBetaUserContactFolderChildFolderDelta | Minor changes |
| Get-MgBetaUserContactFolderContact | Minor changes |
| Get-MgBetaUserContactFolderContactDelta | Minor changes |
| Get-MgBetaUserContactFolderContactExtension | Minor changes |
| Get-MgBetaUserContactFolderDelta | Minor changes |
| Get-MgBetaUserCreatedObjectAsServicePrincipal | Minor changes |
| Get-MgBetaUserDeviceDelta | Minor changes |
| Get-MgBetaUserDeviceManagementTroubleshootingEvent | Minor changes |
| Get-MgBetaUserDeviceMemberOf | Minor changes |
| Get-MgBetaUserDeviceMemberOfAsAdministrativeUnit | Minor changes |
| Get-MgBetaUserDeviceRegisteredOwnerAsServicePrincipal | Minor changes |
| Get-MgBetaUserDeviceRegisteredUserAsServicePrincipal | Minor changes |
| Get-MgBetaUserDeviceTransitiveMemberOf | Minor changes |
| Get-MgBetaUserDeviceUsageRights | Minor changes |
| Get-MgBetaUserDirectReportAsUser | Minor changes |
| Get-MgBetaUserDriveContentTypeBaseType | Minor changes |
| Get-MgBetaUserDriveItem | Minor changes |
| Get-MgBetaUserDriveItemActivityByInterval | Minor changes |
| Get-MgBetaUserDriveItemAnalyticItemActivityStat | Minor changes |
| Get-MgBetaUserDriveItemChild | Minor changes |
| Get-MgBetaUserDriveItemDelta | Minor changes |
| Get-MgBetaUserDriveItemListItemActivityByInterval | Minor changes |
| Get-MgBetaUserDriveItemListItemDocumentSetVersion | Minor changes |
| Get-MgBetaUserDriveItemVersion | Minor changes |
| Get-MgBetaUserDriveListContentType | Minor changes |
| Get-MgBetaUserDriveListContentTypeCompatibleHubContentType | Minor changes |
| Get-MgBetaUserDriveListItemActivityByInterval | Minor changes |
| Get-MgBetaUserDriveListItemDelta | Minor changes |
| Get-MgBetaUserDriveListItemPermission | Minor changes |
| Get-MgBetaUserDriveRootActivityByInterval | Minor changes |
| Get-MgBetaUserDriveRootDelta | Minor changes |
| Get-MgBetaUserDriveRootListItemActivityByInterval | Minor changes |
| Get-MgBetaUserDriveRootListItemDocumentSetVersion | Minor changes |
| Get-MgBetaUserDriveRootVersion | Minor changes |
| Get-MgBetaUserDriveSpecial | Minor changes |
| Get-MgBetaUserEventAttachment | Minor changes |
| Get-MgBetaUserEventDelta | Minor changes |
| Get-MgBetaUserEventExceptionOccurrence | Minor changes |
| Get-MgBetaUserEventExceptionOccurrenceExtension | Minor changes |
| Get-MgBetaUserEventExceptionOccurrenceInstance | Minor changes |
| Get-MgBetaUserEventInstance | Minor changes |
| Get-MgBetaUserEventInstanceDelta | Minor changes |
| Get-MgBetaUserExtension | Minor changes |
| Get-MgBetaUserFollowedSite | Minor changes |
| Get-MgBetaUserInformationProtectionDataLossPreventionPolicy | Minor changes |
| Get-MgBetaUserInformationProtectionSensitivityLabel | Minor changes |
| Get-MgBetaUserInformationProtectionSensitivityLabelSublabel | Minor changes |
| Get-MgBetaUserInformationProtectionThreatAssessmentRequest | Minor changes |
| Get-MgBetaUserInsightShared | Minor changes |
| Get-MgBetaUserInsightTrending | Minor changes |
| Get-MgBetaUserLicenseDetail | Minor changes |
| Get-MgBetaUserLicenseDetailCount | Minor changes |
| Get-MgBetaUserLicenseDetailTeamLicensingDetail | Minor changes |
| Get-MgBetaUserMailFolderChildFolderDelta | Minor changes |
| Get-MgBetaUserMailFolderChildFolderMessage | Minor changes |
| Get-MgBetaUserMailFolderChildFolderMessageDelta | Minor changes |
| Get-MgBetaUserMailFolderChildFolderMessageRule | Minor changes |
| Get-MgBetaUserMailFolderDelta | Minor changes |
| Get-MgBetaUserMailFolderMessage | Minor changes |
| Get-MgBetaUserMailFolderMessageDelta | Minor changes |
| Get-MgBetaUserManagedAppRegistration | Minor changes |
| Get-MgBetaUserManagedDeviceAssignmentFilterEvaluationStatusDetail | Minor changes |
| Get-MgBetaUserManagedDeviceCloudPcRemoteActionResult | Minor changes |
| Get-MgBetaUserManagedDeviceCloudPcReviewStatus | Minor changes |
| Get-MgBetaUserManagedDeviceCompliancePolicyState | Minor changes |
| Get-MgBetaUserManagedDeviceConfigurationState | Minor changes |
| Get-MgBetaUserManagedDeviceDetectedApp | Minor changes |
| Get-MgBetaUserManagedDeviceFileVaultKey | Minor changes |
| Get-MgBetaUserManagedDeviceLogCollectionResponse | Minor changes |
| Get-MgBetaUserManagedDeviceMobileAppConfigurationState | Minor changes |
| Get-MgBetaUserManagedDeviceNonCompliantSetting | Minor changes |
| Get-MgBetaUserManagedDeviceSecurityBaselineStateSettingState | Minor changes |
| Get-MgBetaUserMemberOfAsDirectoryRole | Minor changes |
| Get-MgBetaUserMessageAttachment | Minor changes |
| Get-MgBetaUserMessageDelta | Minor changes |
| Get-MgBetaUserMobileAppIntentAndState | Minor changes |
| Get-MgBetaUserNotification | Minor changes |
| Get-MgBetaUserOauth2PermissionGrant | Minor changes |
| Get-MgBetaUserOnenoteNotebookFromWebUrl | Minor changes |
| Get-MgBetaUserOnenoteNotebookSectionGroup | Minor changes |
| Get-MgBetaUserOnenotePage | Minor changes |
| Get-MgBetaUserOnenoteResource | Minor changes |
| Get-MgBetaUserOnenoteSectionGroup | Minor changes |
| Get-MgBetaUserOnlineMeetingAiInsight | Minor changes |
| Get-MgBetaUserOnlineMeetingAiInsightCount | Minor changes |
| Get-MgBetaUserOnlineMeetingJoinWebUrlVirtualAppointmentJoinWebUrl | Minor changes |
| Get-MgBetaUserOnlineMeetingRecording | Minor changes |
| Get-MgBetaUserOnlineMeetingRecordingContent | Minor changes |
| Get-MgBetaUserOnlineMeetingRecordingCount | Minor changes |
| Get-MgBetaUserOnlineMeetingRecordingDelta | Minor changes |
| Get-MgBetaUserOnlineMeetingTranscript | Minor changes |
| Get-MgBetaUserOnlineMeetingTranscriptContent | Minor changes |
| Get-MgBetaUserOnlineMeetingTranscriptCount | Minor changes |
| Get-MgBetaUserOnlineMeetingTranscriptDelta | Minor changes |
| Get-MgBetaUserOnlineMeetingTranscriptMetadataContent | Minor changes |
| Get-MgBetaUserOnlineMeetingVirtualAppointmentJoinWebUrl | Minor changes |
| Get-MgBetaUserOutlookTaskFolderTaskAttachment | Minor changes |
| Get-MgBetaUserOutlookTaskGroupTaskFolderTaskAttachment | Minor changes |
| Get-MgBetaUserOwnedDeviceAsDevice | Minor changes |
| Get-MgBetaUserOwnedObjectAsApplication | Minor changes |
| Get-MgBetaUserOwnedObjectAsGroup | Minor changes |
| Get-MgBetaUserPlannerAllDelta | Minor changes |
| Get-MgBetaUserPlannerMyDayTask | Minor changes |
| Get-MgBetaUserPlannerPlanDelta | Minor changes |
| Get-MgBetaUserPlannerRecentPlan | Minor changes |
| Get-MgBetaUserPlannerRosterPlan | Minor changes |
| Get-MgBetaUserPlannerTaskDelta | Minor changes |
| Get-MgBetaUserProfileAccount | Minor changes |
| Get-MgBetaUserProfileAddress | Minor changes |
| Get-MgBetaUserProfileAnniversary | Minor changes |
| Get-MgBetaUserProfileLanguage | Minor changes |
| Get-MgBetaUserProfileName | Minor changes |
| Get-MgBetaUserProfilePatent | Minor changes |
| Get-MgBetaUserProfilePhone | Minor changes |
| Get-MgBetaUserProfileWebAccount | Minor changes |
| Get-MgBetaUserProfileWebsite | Minor changes |
| Get-MgBetaUserSecurityInformationProtectionSensitivityLabel | Minor changes |
| Get-MgBetaUserSettingStorageQuotaService | Minor changes |
| Get-MgBetaUserSettingWindows | Minor changes |
| Get-MgBetaUserSettingWindowsInstance | Minor changes |
| Get-MgBetaUserSponsor | Minor changes |
| Get-MgBetaUserTeamworkInstalledApp | Minor changes |
| Get-MgBetaUserTodoList | Minor changes |
| Get-MgBetaUserTodoListDelta | Minor changes |
| Get-MgBetaUserTodoListExtension | Minor changes |
| Get-MgBetaUserTodoTask | Minor changes |
| Get-MgBetaUserTodoTaskChecklistItem | Minor changes |
| Get-MgBetaUserTodoTaskDelta | Minor changes |
| Get-MgBetaUserTransitiveMemberOf | Minor changes |
| Get-MgBetaUserTransitiveMemberOfAsAdministrativeUnit | Minor changes |
| Get-MgBetaUserTransitiveReport | Minor changes |
| Get-MgBetaVirtualEventPresenter | Minor changes |
| Get-MgBetaVirtualEventSession | Minor changes |
| Get-MgBetaVirtualEventSessionAttendanceReport | Minor changes |
| Get-MgBetaVirtualEventSessionAttendanceReportAttendanceRecord | Minor changes |
| Get-MgBetaVirtualEventSessionPresenter | Minor changes |
| Get-MgBetaVirtualEventTownhallByUserIdAndRole | Minor changes |
| Get-MgBetaVirtualEventTownhallByUserRole | Minor changes |
| Get-MgBetaVirtualEventTownhallPresenter | Minor changes |
| Get-MgBetaVirtualEventTownhallPresenterSession | Minor changes |
| Get-MgBetaVirtualEventTownhallSessionAttendanceReportAttendanceRecord | Minor changes |
| Get-MgBetaVirtualEventWebinarPresenterSession | Minor changes |
| Get-MgBetaVirtualEventWebinarSessionAttendanceReport | Minor changes |
| Get-MgBetaWindowsUpdatesDeploymentAudienceExclusion | Minor changes |
| Grant-MgBetaGroupDriveItemListItemPermission | Minor changes |
| Grant-MgBetaGroupDriveItemPermission | Minor changes |
| Grant-MgBetaGroupDriveListItemPermission | Minor changes |
| Grant-MgBetaGroupDriveListPermission | Minor changes |
| Grant-MgBetaGroupDriveRootListItemPermission | Minor changes |
| Grant-MgBetaGroupDriveRootPermission | Minor changes |
| Grant-MgBetaGroupSiteListItemPermission | Minor changes |
| Grant-MgBetaGroupSiteListPermission | Minor changes |
| Grant-MgBetaGroupSitePermission | Minor changes |
| Grant-MgBetaUserDriveItemListItemPermission | Minor changes |
| Grant-MgBetaUserDriveItemPermission | Minor changes |
| Grant-MgBetaUserDriveListItemPermission | Minor changes |
| Grant-MgBetaUserDriveListPermission | Minor changes |
| Grant-MgBetaUserDriveRootListItemPermission | Minor changes |
| Grant-MgBetaUserDriveRootPermission | Minor changes |
| Hide-MgBetaUserChatForUser | Minor changes |
| Import-MgBetaDeviceManagementDepOnboardingSettingImportedAppleDeviceIdentityAppleDeviceIdentityList | Minor changes |
| Import-MgBetaDeviceManagementImportedDeviceIdentityList | Minor changes |
| Import-MgBetaDeviceManagementImportedWindowsAutopilotDeviceIdentity | Minor changes |
| Import-MgBetaRoleManagementCloudPcResourceNamespaceResourceAction | Minor changes |
| Import-MgBetaRoleManagementDefenderResourceNamespaceResourceAction | Minor changes |
| Import-MgBetaRoleManagementDeviceManagementResourceNamespaceResourceAction | Minor changes |
| Import-MgBetaRoleManagementExchangeResourceNamespaceResourceAction | Minor changes |
| Initialize-MgBetaUserManagedDeviceEsim | Minor changes |
| Invoke-MgBetaAcceptGroupEvent | Minor changes |
| Invoke-MgBetaAcceptGroupEventTentatively | Minor changes |
| Invoke-MgBetaAcceptUserEvent | Minor changes |
| Invoke-MgBetaAcceptUserEventInstance | Minor changes |
| Invoke-MgBetaAcceptUserEventInstanceTentatively | Minor changes |
| Invoke-MgBetaAcceptUserEventTentatively | Minor changes |
| Invoke-MgBetaAccountDeviceManagementWindowsAutopilotDeviceIdentity | Minor changes |
| Invoke-MgBetaAllowDeviceManagementWindowsAutopilotDeploymentProfileAssignedDeviceNextEnrollment | Minor changes |
| Invoke-MgBetaAllowDeviceManagementWindowsAutopilotDeviceIdentityNextEnrollment | Minor changes |
| Invoke-MgBetaAppUserManagedDeviceDiagnostic | Minor changes |
| Invoke-MgBetaArchiveGroupPlannerPlan | Minor changes |
| Invoke-MgBetaArchiveUserPlannerPlan | Minor changes |
| Invoke-MgBetaAssignedRoleManagementCloudPcRoleDefinitionPrincipal | Minor changes |
| Invoke-MgBetaAssignedRoleManagementDefenderRoleDefinitionPrincipal | Minor changes |
| Invoke-MgBetaAssignedRoleManagementDeviceManagementRoleDefinitionPrincipal | Minor changes |
| Invoke-MgBetaAssignedRoleManagementExchangeRoleDefinitionPrincipal | Minor changes |
| Invoke-MgBetaBufferGroupSiteInformationProtectionDecrypt | Minor changes |
| Invoke-MgBetaBufferGroupSiteInformationProtectionEncrypt | Minor changes |
| Invoke-MgBetaBufferUserInformationProtectionDecrypt | Minor changes |
| Invoke-MgBetaBufferUserInformationProtectionEncrypt | Minor changes |
| Invoke-MgBetaBulkUserManagedDeviceSetCloudPcReviewStatus | Minor changes |
| Invoke-MgBetaCalendarGroupCalendar | Minor changes |
| Invoke-MgBetaCheckinGroupDriveItem | Minor changes |
| Invoke-MgBetaCheckinGroupDriveRoot | Minor changes |
| Invoke-MgBetaCheckinUserDriveItem | Minor changes |
| Invoke-MgBetaCheckinUserDriveRoot | Minor changes |
| Invoke-MgBetaCheckoutGroupDriveItem | Minor changes |
| Invoke-MgBetaCheckoutGroupDriveRoot | Minor changes |
| Invoke-MgBetaCheckoutUserDriveItem | Minor changes |
| Invoke-MgBetaCheckoutUserDriveRoot | Minor changes |
| Invoke-MgBetaCleanUserManagedDeviceWindowsDevice | Minor changes |
| Invoke-MgBetaCreationUserAuthenticationFido2MethodOption | Minor changes |
| Invoke-MgBetaDeactivateSolutionBackupRestoreProtectionPolicy | Minor changes |
| Invoke-MgBetaDeactivateSolutionBackupRestoreServiceApp | Minor changes |
| Invoke-MgBetaDeclineGroupEvent | Minor changes |
| Invoke-MgBetaDeclineUserEvent | Minor changes |
| Invoke-MgBetaDeclineUserEventInstance | Minor changes |
| Invoke-MgBetaDeprovisionUserManagedDevice | Minor changes |
| Invoke-MgBetaDismissGroupEventReminder | Minor changes |
| Invoke-MgBetaDismissUserEventInstanceReminder | Minor changes |
| Invoke-MgBetaDismissUserEventReminder | Minor changes |
| Invoke-MgBetaDownUserManagedDeviceShut | Minor changes |
| Invoke-MgBetaDownloadUserManagedDeviceAppDiagnostic | Minor changes |
| Invoke-MgBetaEnrollUserManagedDeviceNowAction | Minor changes |
| Invoke-MgBetaExecuteUserManagedDeviceAction | Minor changes |
| Invoke-MgBetaExtractGroupDriveItemSensitivityLabel | Minor changes |
| Invoke-MgBetaExtractGroupDriveRootSensitivityLabel | Minor changes |
| Invoke-MgBetaExtractGroupSiteInformationProtectionPolicyLabel | Minor changes |
| Invoke-MgBetaExtractUserDriveItemSensitivityLabel | Minor changes |
| Invoke-MgBetaExtractUserDriveRootSensitivityLabel | Minor changes |
| Invoke-MgBetaExtractUserInformationProtectionPolicyLabel | Minor changes |
| Invoke-MgBetaExtractUserSecurityInformationProtectionSensitivityLabelContentLabel | Minor changes |
| Invoke-MgBetaFollowGroupDriveItem | Minor changes |
| Invoke-MgBetaFollowGroupDriveRoot | Minor changes |
| Invoke-MgBetaFollowUserDriveItem | Minor changes |
| Invoke-MgBetaFollowUserDriveRoot | Minor changes |
| Invoke-MgBetaForwardGroupEvent | Minor changes |
| Invoke-MgBetaForwardUserEvent | Minor changes |
| Invoke-MgBetaForwardUserEventInstance | Minor changes |
| Invoke-MgBetaForwardUserMailFolderChildFolderMessage | Minor changes |
| Invoke-MgBetaForwardUserMailFolderMessage | Minor changes |
| Invoke-MgBetaForwardUserMessage | Minor changes |
| Invoke-MgBetaGraphDeviceManagementDepOnboardingSetting | Minor changes |
| Invoke-MgBetaGraphGroupDrive | Minor changes |
| Invoke-MgBetaGraphUserChat | Minor changes |
| Invoke-MgBetaGraphUserDrive | Minor changes |
| Invoke-MgBetaHasDeviceManagementDeviceEnrollmentConfigurationPayloadLink | Minor changes |
| Invoke-MgBetaHasDeviceManagementWindowsAutopilotDeploymentProfilePayloadLink | Minor changes |
| Invoke-MgBetaHasUserDeviceEnrollmentConfigurationPayloadLink | Minor changes |
| Invoke-MgBetaInitiateUserManagedDeviceAttestation | Minor changes |
| Invoke-MgBetaInitiateUserManagedDeviceMobileDeviceManagementKeyRecovery | Minor changes |
| Invoke-MgBetaInitiateUserManagedDeviceOnDemandProactiveRemediation | Minor changes |
| Invoke-MgBetaInviteGroupDriveItem | Minor changes |
| Invoke-MgBetaInviteGroupDriveRoot | Minor changes |
| Invoke-MgBetaInviteUserDriveItem | Minor changes |
| Invoke-MgBetaInviteUserDriveRoot | Minor changes |
| Invoke-MgBetaLogoutUserManagedDeviceSharedAppleDeviceActiveUser | Minor changes |
| Invoke-MgBetaMarkUserChatReadForUser | Minor changes |
| Invoke-MgBetaMarkUserChatUnreadForUser | Minor changes |
| Invoke-MgBetaMarkUserMailFolderChildFolderMessageAsJunk | Minor changes |
| Invoke-MgBetaMarkUserMailFolderChildFolderMessageAsNotJunk | Minor changes |
| Invoke-MgBetaMarkUserMailFolderMessageAsJunk | Minor changes |
| Invoke-MgBetaMarkUserMailFolderMessageAsNotJunk | Minor changes |
| Invoke-MgBetaMarkUserMessageAsJunk | Minor changes |
| Invoke-MgBetaMarkUserMessageAsNotJunk | Minor changes |
| Invoke-MgBetaMessageUserChat | Minor changes |
| Invoke-MgBetaOverrideUserManagedDeviceComplianceState | Minor changes |
| Invoke-MgBetaPlayUserManagedDeviceLostModeSound | Minor changes |
| Invoke-MgBetaPreviewGroupDriveItem | Minor changes |
| Invoke-MgBetaPreviewGroupDriveRoot | Minor changes |
| Invoke-MgBetaPreviewGroupOnenotePage | Minor changes |
| Invoke-MgBetaPreviewSiteOnenoteNotebookSectionGroupSectionPage | Minor changes |
| Invoke-MgBetaPreviewSiteOnenoteNotebookSectionPage | Minor changes |
| Invoke-MgBetaPreviewSiteOnenotePage | Minor changes |
| Invoke-MgBetaPreviewSiteOnenoteSectionGroupSectionPage | Minor changes |
| Invoke-MgBetaPreviewSiteOnenoteSectionPage | Minor changes |
| Invoke-MgBetaPreviewUserDriveItem | Minor changes |
| Invoke-MgBetaPreviewUserDriveRoot | Minor changes |
| Invoke-MgBetaPreviewUserOnenotePage | Minor changes |
| Invoke-MgBetaReauthorizeGroupDriveItemSubscription | Minor changes |
| Invoke-MgBetaReauthorizeGroupDriveListSubscription | Minor changes |
| Invoke-MgBetaReauthorizeGroupDriveRootSubscription | Minor changes |
| Invoke-MgBetaReauthorizeGroupSiteListSubscription | Minor changes |
| Invoke-MgBetaReauthorizeUserDriveItemSubscription | Minor changes |
| Invoke-MgBetaReauthorizeUserDriveListSubscription | Minor changes |
| Invoke-MgBetaReauthorizeUserDriveRootSubscription | Minor changes |
| Invoke-MgBetaRecentGroupDrive | Minor changes |
| Invoke-MgBetaRecentUserActivity | Minor changes |
| Invoke-MgBetaRecentUserDrive | Minor changes |
| Invoke-MgBetaReenableUserManagedDevice | Minor changes |
| Invoke-MgBetaReplyAllUserMailFolderChildFolderMessage | Minor changes |
| Invoke-MgBetaReplyAllUserMailFolderMessage | Minor changes |
| Invoke-MgBetaReplyAllUserMessage | Minor changes |
| Invoke-MgBetaReplyUserMailFolderChildFolderMessage | Minor changes |
| Invoke-MgBetaReplyUserMailFolderMessage | Minor changes |
| Invoke-MgBetaReplyUserMessage | Minor changes |
| Invoke-MgBetaRetireUserManagedDevice | Minor changes |
| Invoke-MgBetaRotateUserManagedDeviceBitLockerKey | Minor changes |
| Invoke-MgBetaRotateUserManagedDeviceFileVaultKey | Minor changes |
| Invoke-MgBetaRotateUserManagedDeviceLocalAdminPassword | Minor changes |
| Invoke-MgBetaScanUserManagedDeviceWindowsDefender | Minor changes |
| Invoke-MgBetaShareDeviceManagementDepOnboardingSettingForSchoolDataSyncService | Minor changes |
| Invoke-MgBetaSignGroupSiteInformationProtectionDigest | Minor changes |
| Invoke-MgBetaSignUserInformationProtectionDigest | Minor changes |
| Invoke-MgBetaSnoozeGroupEventReminder | Minor changes |
| Invoke-MgBetaSnoozeUserEventInstanceReminder | Minor changes |
| Invoke-MgBetaSnoozeUserEventReminder | Minor changes |
| Invoke-MgBetaSoftUserChatMessageDelete | Minor changes |
| Invoke-MgBetaSoftUserChatMessageReplyDelete | Minor changes |
| Invoke-MgBetaSupportedUserOutlookLanguage | Minor changes |
| Invoke-MgBetaTargetDeviceAppManagementManagedAppPolicyApp | Minor changes |
| Invoke-MgBetaTargetDeviceAppManagementManagedAppRegistrationAppliedPolicyApp | Minor changes |
| Invoke-MgBetaTargetDeviceAppManagementManagedAppRegistrationIntendedPolicyApp | Minor changes |
| Invoke-MgBetaTargetDeviceAppManagementWindowsManagedAppProtectionApp | Minor changes |
| Invoke-MgBetaTimeUserOutlook | Minor changes |
| Invoke-MgBetaUnarchiveGroupPlannerPlan | Minor changes |
| Invoke-MgBetaUnarchiveUserPlannerPlan | Minor changes |
| Invoke-MgBetaUnassignDeviceManagementWindowsAutopilotDeploymentProfileAssignedDeviceUserFromDevice | Minor changes |
| Invoke-MgBetaUnassignDeviceManagementWindowsAutopilotDeviceIdentityUserFromDevice | Minor changes |
| Invoke-MgBetaUnfollowGroupDriveItem | Minor changes |
| Invoke-MgBetaUnfollowGroupDriveRoot | Minor changes |
| Invoke-MgBetaUnfollowUserDriveItem | Minor changes |
| Invoke-MgBetaUnfollowUserDriveRoot | Minor changes |
| Invoke-MgBetaUnsubscribeUserMailFolderChildFolderMessage | Minor changes |
| Invoke-MgBetaUnsubscribeUserMailFolderMessage | Minor changes |
| Invoke-MgBetaUnsubscribeUserMessage | Minor changes |
| Invoke-MgBetaUploadDeviceManagementDepOnboardingSettingDepToken | Minor changes |
| Invoke-MgBetaUploadEducationSynchronizationProfileUrl | Minor changes |
| Join-MgBetaGroupDriveListContentTypeWithHubSite | Minor changes |
| Join-MgBetaGroupSiteContentTypeWithHubSite | Minor changes |
| Join-MgBetaGroupSiteListContentTypeWithHubSite | Minor changes |
| Join-MgBetaUserDriveListContentTypeWithHubSite | Minor changes |
| Lock-MgBetaUserManagedDeviceRemote | Minor changes |
| Move-MgBetaGroupPlannerPlanToContainer | Minor changes |
| Move-MgBetaUserMailFolder | Minor changes |
| Move-MgBetaUserMailFolderChildFolder | Minor changes |
| Move-MgBetaUserMailFolderChildFolderMessage | Minor changes |
| Move-MgBetaUserMailFolderMessage | Minor changes |
| Move-MgBetaUserManagedDeviceToOu | Minor changes |
| Move-MgBetaUserMessage | Minor changes |
| New-MgBetaChatMessage | Minor changes |
| New-MgBetaChatPinnedMessage | Minor changes |
| New-MgBetaCommunicationCallContentSharingSession | Minor changes |
| New-MgBetaDeviceAppManagementAndroidManagedAppProtectionApp | Minor changes |
| New-MgBetaDeviceAppManagementDefaultManagedAppProtection | Minor changes |
| New-MgBetaDeviceAppManagementDefaultManagedAppProtectionApp | Minor changes |
| New-MgBetaDeviceAppManagementManagedAppRegistration | Minor changes |
| New-MgBetaDeviceAppManagementManagedAppRegistrationOperation | Minor changes |
| New-MgBetaDeviceAppManagementMdmWindowsInformationProtectionPolicyExemptAppLockerFile | Minor changes |
| New-MgBetaDeviceAppManagementMdmWindowsInformationProtectionPolicyProtectedAppLockerFile | Minor changes |
| New-MgBetaDeviceAppManagementTargetedManagedAppConfigurationApp | Minor changes |
| New-MgBetaDeviceAppManagementTargetedManagedAppConfigurationSetting | Minor changes |
| New-MgBetaDeviceAppManagementTask | Minor changes |
| New-MgBetaDeviceAppManagementVppToken | Minor changes |
| New-MgBetaDeviceAppManagementWindowsInformationProtectionDeviceRegistration | Minor changes |
| New-MgBetaDeviceAppManagementWindowsInformationProtectionPolicy | Minor changes |
| New-MgBetaDeviceAppManagementWindowsInformationProtectionPolicyExemptAppLockerFile | Minor changes |
| New-MgBetaDeviceAppManagementWindowsInformationProtectionPolicyProtectedAppLockerFile | Minor changes |
| New-MgBetaDeviceAppManagementWindowsInformationProtectionWipeAction | Minor changes |
| New-MgBetaDeviceAppManagementWindowsManagedAppProtection | Minor changes |
| New-MgBetaDeviceAppManagementWindowsManagedAppProtectionApp | Minor changes |
| New-MgBetaDeviceAppManagementiOSManagedAppProtectionApp | Minor changes |
| New-MgBetaDeviceManagementAndroidDeviceOwnerEnrollmentProfileToken | Minor changes |
| New-MgBetaDeviceManagementAndroidForWorkEnrollmentProfileToken | Minor changes |
| New-MgBetaDeviceManagementDepOnboardingSettingEncryptionPublicKey | Minor changes |
| New-MgBetaDeviceManagementDeviceEnrollmentConfigurationEnrollmentNotificationConfiguration | Minor changes |
| New-MgBetaDirectoryCertificateAuthorityCertificateBasedApplicationConfiguration | Minor changes |
| New-MgBetaDirectoryCertificateAuthorityCertificateBasedApplicationConfigurationTrustedCertificateAuthority | Minor changes |
| New-MgBetaGroupDriveItemLink | Minor changes |
| New-MgBetaGroupDriveItemListItemLink | Minor changes |
| New-MgBetaGroupDriveItemUploadSession | Minor changes |
| New-MgBetaGroupDriveListItemLink | Minor changes |
| New-MgBetaGroupDriveRootLink | Minor changes |
| New-MgBetaGroupDriveRootListItemLink | Minor changes |
| New-MgBetaGroupDriveRootUploadSession | Minor changes |
| New-MgBetaGroupSiteListItemLink | Minor changes |
| New-MgBetaGroupTeamChannelMember | Minor changes |
| New-MgBetaGroupTeamPrimaryChannelMember | Minor changes |
| New-MgBetaSecurityThreatSubmissionEmailThreat | Minor changes |
| New-MgBetaSecurityThreatSubmissionFileThreat | Minor changes |
| New-MgBetaSecurityThreatSubmissionUrlThreat | Minor changes |
| New-MgBetaTeamChannelMember | Minor changes |
| New-MgBetaTeamPrimaryChannelMember | Minor changes |
| New-MgBetaTeamworkDeletedTeamChannelMember | Minor changes |
| New-MgBetaUserDeviceEnrollmentConfigurationEnrollmentNotificationConfiguration | Minor changes |
| New-MgBetaUserDriveItemLink | Minor changes |
| New-MgBetaUserDriveItemListItemLink | Minor changes |
| New-MgBetaUserDriveItemUploadSession | Minor changes |
| New-MgBetaUserDriveListItemLink | Minor changes |
| New-MgBetaUserDriveRootLink | Minor changes |
| New-MgBetaUserDriveRootListItemLink | Minor changes |
| New-MgBetaUserDriveRootUploadSession | Minor changes |
| New-MgBetaUserEventAttachmentUploadSession | Minor changes |
| New-MgBetaUserEventInstanceAttachmentUploadSession | Minor changes |
| New-MgBetaUserMailFolderChildFolderMessageAttachmentUploadSession | Minor changes |
| New-MgBetaUserMailFolderChildFolderMessageForward | Minor changes |
| New-MgBetaUserMailFolderChildFolderMessageReply | Minor changes |
| New-MgBetaUserMailFolderChildFolderMessageReplyAll | Minor changes |
| New-MgBetaUserMailFolderMessageAttachmentUploadSession | Minor changes |
| New-MgBetaUserMailFolderMessageForward | Minor changes |
| New-MgBetaUserMailFolderMessageReply | Minor changes |
| New-MgBetaUserMailFolderMessageReplyAll | Minor changes |
| New-MgBetaUserMessageAttachmentUploadSession | Minor changes |
| New-MgBetaUserMessageForward | Minor changes |
| New-MgBetaUserMessageReply | Minor changes |
| New-MgBetaUserMessageReplyAll | Minor changes |
| New-MgBetaUserMobileAppTroubleshootingEventAppLogCollectionRequestDownloadUrl | Minor changes |
| New-MgBetaUserOutlookTaskAttachmentUploadSession | Minor changes |
| New-MgBetaUserOutlookTaskFolderTaskAttachmentUploadSession | Minor changes |
| New-MgBetaUserOutlookTaskGroupTaskFolderTaskAttachmentUploadSession | Minor changes |
| New-MgBetaUserTodoListTaskAttachmentUploadSession | Minor changes |
| Publish-MgBetaGroupDriveListContentType | Minor changes |
| Publish-MgBetaGroupSiteContentType | Minor changes |
| Publish-MgBetaGroupSiteListContentType | Minor changes |
| Publish-MgBetaUserDriveListContentType | Minor changes |
| Remove-MgBetaDeviceAppManagementAndroidManagedAppProtectionApp | Minor changes |
| Remove-MgBetaDeviceAppManagementAndroidManagedAppProtectionAssignment | Minor changes |
| Remove-MgBetaDeviceAppManagementDefaultManagedAppProtection | Minor changes |
| Remove-MgBetaDeviceAppManagementDefaultManagedAppProtectionApp | Minor changes |
| Remove-MgBetaDeviceAppManagementManagedAppRegistrationOperation | Minor changes |
| Remove-MgBetaDeviceAppManagementMdmWindowsInformationProtectionPolicyAssignment | Minor changes |
| Remove-MgBetaDeviceAppManagementMdmWindowsInformationProtectionPolicyExemptAppLockerFile | Minor changes |
| Remove-MgBetaDeviceAppManagementMdmWindowsInformationProtectionPolicyProtectedAppLockerFile | Minor changes |
| Remove-MgBetaDeviceAppManagementTargetedManagedAppConfigurationApp | Minor changes |
| Remove-MgBetaDeviceAppManagementTargetedManagedAppConfigurationAssignment | Minor changes |
| Remove-MgBetaDeviceAppManagementTargetedManagedAppConfigurationSetting | Minor changes |
| Remove-MgBetaDeviceAppManagementTask | Minor changes |
| Remove-MgBetaDeviceAppManagementVppToken | Minor changes |
| Remove-MgBetaDeviceAppManagementWindowsInformationProtectionDeviceRegistration | Minor changes |
| Remove-MgBetaDeviceAppManagementWindowsInformationProtectionPolicy | Minor changes |
| Remove-MgBetaDeviceAppManagementWindowsInformationProtectionPolicyAssignment | Minor changes |
| Remove-MgBetaDeviceAppManagementWindowsInformationProtectionPolicyExemptAppLockerFile | Minor changes |
| Remove-MgBetaDeviceAppManagementWindowsInformationProtectionPolicyProtectedAppLockerFile | Minor changes |
| Remove-MgBetaDeviceAppManagementWindowsInformationProtectionWipeAction | Minor changes |
| Remove-MgBetaDeviceAppManagementWindowsManagedAppProtection | Minor changes |
| Remove-MgBetaDeviceAppManagementWindowsManagedAppProtectionApp | Minor changes |
| Remove-MgBetaDeviceAppManagementWindowsManagedAppProtectionAssignment | Minor changes |
| Remove-MgBetaDeviceAppManagementiOSManagedAppProtectionApp | Minor changes |
| Remove-MgBetaDeviceAppManagementiOSManagedAppProtectionAssignment | Minor changes |
| Remove-MgBetaDirectoryCertificateAuthorityCertificateBasedApplicationConfiguration | Minor changes |
| Remove-MgBetaDirectoryCertificateAuthorityCertificateBasedApplicationConfigurationTrustedCertificateAuthority | Minor changes |
| Remove-MgBetaEducationSynchronizationProfile | Minor changes |
| Remove-MgBetaEntitlementManagementAccessPackageCatalogCustomAccessPackageWorkflowExtension | Minor changes |
| Remove-MgBetaGroupCalendarPermanent | Minor changes |
| Remove-MgBetaGroupConversation | Minor changes |
| Remove-MgBetaGroupDriveItemCheckout | Minor changes |
| Remove-MgBetaGroupDriveItemPermanent | Minor changes |
| Remove-MgBetaGroupDriveRootCheckout | Minor changes |
| Remove-MgBetaGroupDriveRootPermanent | Minor changes |
| Remove-MgBetaGroupEventPermanent | Minor changes |
| Remove-MgBetaGroupSite | Minor changes |
| Remove-MgBetaGroupSiteContentModelFromDrive | Minor changes |
| Remove-MgBetaGroupTeamChannelMember | Minor changes |
| Remove-MgBetaGroupTeamPrimaryChannelMember | Minor changes |
| Remove-MgBetaSecurityAttackSimulation | Minor changes |
| Remove-MgBetaSecurityIdentitySensor | Minor changes |
| Remove-MgBetaTeamChannelMember | Minor changes |
| Remove-MgBetaTeamPrimaryChannelMember | Minor changes |
| Remove-MgBetaTeamScheduleShift | Minor changes |
| Remove-MgBetaTeamworkDeletedTeamChannelMember | Minor changes |
| Remove-MgBetaUserAuthenticationFido2Method | Minor changes |
| Remove-MgBetaUserCalendarPermanent | Minor changes |
| Remove-MgBetaUserChatAccessForUser | Minor changes |
| Remove-MgBetaUserContactFolderChildFolderContactPermanent | Minor changes |
| Remove-MgBetaUserContactFolderChildFolderPermanent | Minor changes |
| Remove-MgBetaUserContactFolderContactPermanent | Minor changes |
| Remove-MgBetaUserContactFolderPermanent | Minor changes |
| Remove-MgBetaUserContactPermanent | Minor changes |
| Remove-MgBetaUserDriveItemCheckout | Minor changes |
| Remove-MgBetaUserDriveItemPermanent | Minor changes |
| Remove-MgBetaUserDriveRootCheckout | Minor changes |
| Remove-MgBetaUserDriveRootPermanent | Minor changes |
| Remove-MgBetaUserEventInstancePermanent | Minor changes |
| Remove-MgBetaUserEventPermanent | Minor changes |
| Remove-MgBetaUserFollowedSite | Minor changes |
| Remove-MgBetaUserMailFolderChildFolderMessagePermanent | Minor changes |
| Remove-MgBetaUserMailFolderChildFolderPermanent | Minor changes |
| Remove-MgBetaUserMailFolderMessagePermanent | Minor changes |
| Remove-MgBetaUserMailFolderPermanent | Minor changes |
| Remove-MgBetaUserManagedDeviceFirmwareConfigurationInterfaceManagement | Minor changes |
| Remove-MgBetaUserManagedDeviceUserFromSharedAppleDevice | Minor changes |
| Remove-MgBetaUserMessagePermanent | Minor changes |
| Remove-MgBetaUserOutlookTaskFolderPermanent | Minor changes |
| Remove-MgBetaUserOutlookTaskFolderTaskPermanent | Minor changes |
| Remove-MgBetaUserOutlookTaskGroupTaskFolderPermanent | Minor changes |
| Remove-MgBetaUserOutlookTaskGroupTaskFolderTaskPermanent | Minor changes |
| Remove-MgBetaUserOutlookTaskPermanent | Minor changes |
| Remove-MgBetaWindowsUpdatesPolicyComplianceChange | Minor changes |
| Remove-MgBetaWindowsUpdatesUpdatableAsset | Minor changes |
| Rename-MgBetaUserManagedDeviceAssignment | Minor changes |
| Request-MgBetaUserManagedDeviceRemoteAssistance | Minor changes |
| Reset-MgBetaEducationSynchronizationProfile | Minor changes |
| Reset-MgBetaUserAuthenticationMethodPassword | Minor changes |
| Reset-MgBetaUserManagedDevicePasscode | Minor changes |
| Restart-MgBetaUserManagedDeviceNow | Minor changes |
| Restore-MgBetaGroupDriveItem | Minor changes |
| Restore-MgBetaGroupDriveItemListItemDocumentSetVersion | Minor changes |
| Restore-MgBetaGroupDriveItemListItemVersion | Minor changes |
| Restore-MgBetaGroupDriveItemVersion | Minor changes |
| Restore-MgBetaGroupDriveListItemDocumentSetVersion | Minor changes |
| Restore-MgBetaGroupDriveListItemVersion | Minor changes |
| Restore-MgBetaGroupDriveRoot | Minor changes |
| Restore-MgBetaGroupDriveRootListItemDocumentSetVersion | Minor changes |
| Restore-MgBetaGroupDriveRootListItemVersion | Minor changes |
| Restore-MgBetaGroupDriveRootVersion | Minor changes |
| Restore-MgBetaGroupSiteListItemDocumentSetVersion | Minor changes |
| Restore-MgBetaGroupSiteListItemVersion | Minor changes |
| Restore-MgBetaUserDriveItem | Minor changes |
| Restore-MgBetaUserDriveItemListItemDocumentSetVersion | Minor changes |
| Restore-MgBetaUserDriveItemListItemVersion | Minor changes |
| Restore-MgBetaUserDriveItemVersion | Minor changes |
| Restore-MgBetaUserDriveListItemDocumentSetVersion | Minor changes |
| Restore-MgBetaUserDriveListItemVersion | Minor changes |
| Restore-MgBetaUserDriveRoot | Minor changes |
| Restore-MgBetaUserDriveRootListItemDocumentSetVersion | Minor changes |
| Restore-MgBetaUserDriveRootListItemVersion | Minor changes |
| Restore-MgBetaUserDriveRootVersion | Minor changes |
| Restore-MgBetaUserManagedDevicePasscode | Minor changes |
| Resume-MgBetaEducationSynchronizationProfile | Minor changes |
| Revoke-MgBetaDeviceAppManagementVppTokenLicense | Minor changes |
| Revoke-MgBetaDeviceManagementAndroidDeviceOwnerEnrollmentProfileToken | Minor changes |
| Revoke-MgBetaDeviceManagementAndroidForWorkEnrollmentProfileToken | Minor changes |
| Revoke-MgBetaGroupDriveItemListItemPermissionGrant | Minor changes |
| Revoke-MgBetaGroupDriveItemPermissionGrant | Minor changes |
| Revoke-MgBetaGroupDriveListItemPermissionGrant | Minor changes |
| Revoke-MgBetaGroupDriveListPermissionGrant | Minor changes |
| Revoke-MgBetaGroupDriveRootListItemPermissionGrant | Minor changes |
| Revoke-MgBetaGroupDriveRootPermissionGrant | Minor changes |
| Revoke-MgBetaGroupSiteListItemPermissionGrant | Minor changes |
| Revoke-MgBetaGroupSiteListPermissionGrant | Minor changes |
| Revoke-MgBetaGroupSitePermissionGrant | Minor changes |
| Revoke-MgBetaUserDriveItemListItemPermissionGrant | Minor changes |
| Revoke-MgBetaUserDriveItemPermissionGrant | Minor changes |
| Revoke-MgBetaUserDriveListItemPermissionGrant | Minor changes |
| Revoke-MgBetaUserDriveListPermissionGrant | Minor changes |
| Revoke-MgBetaUserDriveRootListItemPermissionGrant | Minor changes |
| Revoke-MgBetaUserDriveRootPermissionGrant | Minor changes |
| Revoke-MgBetaUserManagedDeviceAppleVppLicense | Minor changes |
| Search-MgBetaDeviceManagementImportedDeviceIdentityExistingIdentity | Minor changes |
| Search-MgBetaGroupDrive | Minor changes |
| Search-MgBetaGroupDriveItem | Minor changes |
| Search-MgBetaGroupDriveRoot | Minor changes |
| Search-MgBetaUserDrive | Minor changes |
| Search-MgBetaUserDriveItem | Minor changes |
| Search-MgBetaUserDriveRoot | Minor changes |
| Send-MgBetaUserChatActivityNotification | Minor changes |
| Send-MgBetaUserMailFolderChildFolderMessage | Minor changes |
| Send-MgBetaUserMailFolderMessage | Minor changes |
| Send-MgBetaUserManagedDeviceCustomNotificationToCompanyPortal | Minor changes |
| Send-MgBetaUserMessage | Minor changes |
| Send-MgBetaUserOnlineMeetingJoinWebUrlVirtualAppointmentReminderSm | Minor changes |
| Send-MgBetaUserOnlineMeetingJoinWebUrlVirtualAppointmentSm | Minor changes |
| Send-MgBetaUserOnlineMeetingVirtualAppointmentReminderSm | Minor changes |
| Send-MgBetaUserOnlineMeetingVirtualAppointmentSm | Minor changes |
| Send-MgBetaUserTeamworkActivityNotification | Minor changes |
| Set-MgBetaDeviceAppManagementWindowsManagedAppProtection | Minor changes |
| Set-MgBetaDeviceManagementAppleUserInitiatedEnrollmentProfilePriority | Minor changes |
| Set-MgBetaDeviceManagementDepOnboardingSettingEnrollmentProfileDefaultProfile | Minor changes |
| Set-MgBetaDeviceManagementDeviceEnrollmentConfiguration | Minor changes |
| Set-MgBetaDeviceManagementDeviceEnrollmentConfigurationPriority | Minor changes |
| Set-MgBetaDeviceManagementWindowsAutopilotDeploymentProfile | Minor changes |
| Set-MgBetaDeviceManagementWindowsAutopilotDeploymentProfileAssignedDeviceUserToDevice | Minor changes |
| Set-MgBetaDeviceManagementWindowsAutopilotDeviceIdentityResourceAccountToDevice | Minor changes |
| Set-MgBetaDeviceManagementWindowsAutopilotDeviceIdentityUserToDevice | Minor changes |
| Set-MgBetaDeviceManagementWindowsFeatureUpdateProfile | Minor changes |
| Set-MgBetaExternalConnectionItem | Minor changes |
| Set-MgBetaGroupDriveItemSensitivityLabel | Minor changes |
| Set-MgBetaGroupDriveRootSensitivityLabel | Minor changes |
| Set-MgBetaUserChatMessageReaction | Minor changes |
| Set-MgBetaUserChatMessageReplyReaction | Minor changes |
| Set-MgBetaUserDeviceEnrollmentConfiguration | Minor changes |
| Set-MgBetaUserDeviceEnrollmentConfigurationPriority | Minor changes |
| Set-MgBetaUserDriveItemSensitivityLabel | Minor changes |
| Set-MgBetaUserDriveRootSensitivityLabel | Minor changes |
| Set-MgBetaUserManagedDeviceCloudPcReviewStatus | Minor changes |
| Set-MgBetaUserManagedDeviceName | Minor changes |
| Set-MgBetaUserPresence | Minor changes |
| Set-MgBetaUserPresenceStatusMessage | Minor changes |
| Set-MgBetaUserPresenceUserPreferredPresence | Minor changes |
| Skip-MgBetaUserManagedDeviceActivationLock | Minor changes |
| Start-MgBetaEducationSynchronizationProfile | Minor changes |
| Start-MgBetaUserManagedDeviceConfigurationManagerAction | Minor changes |
| Stop-MgBetaGroupEvent | Minor changes |
| Stop-MgBetaUserEvent | Minor changes |
| Stop-MgBetaUserEventInstance | Minor changes |
| Suspend-MgBetaEducationSynchronizationProfile | Minor changes |
| Suspend-MgBetaUserManagedDeviceConfigurationRefresh | Minor changes |
| Sync-MgBetaDeviceAppManagementMicrosoftStoreForBusinessApp | Minor changes |
| Sync-MgBetaDeviceAppManagementVppTokenLicense | Minor changes |
| Sync-MgBetaDeviceAppManagementVppTokenLicenseCount | Minor changes |
| Sync-MgBetaDeviceManagementDepOnboardingSettingWithAppleDeviceEnrollmentProgram | Minor changes |
| Sync-MgBetaDeviceManagementWindowsAutopilotSetting | Minor changes |
| Sync-MgBetaUserManagedDevice | Minor changes |
| Test-MgBetaGroupDriveItemPermission | Minor changes |
| Test-MgBetaGroupDriveListContentTypePublished | Minor changes |
| Test-MgBetaGroupDriveRootPermission | Minor changes |
| Test-MgBetaGroupSiteContentTypePublished | Minor changes |
| Test-MgBetaGroupSiteInformationProtectionDataLossPreventionPolicy | Minor changes |
| Test-MgBetaGroupSiteInformationProtectionPolicyLabelApplication | Minor changes |
| Test-MgBetaGroupSiteInformationProtectionPolicyLabelClassificationResult | Minor changes |
| Test-MgBetaGroupSiteInformationProtectionPolicyLabelRemoval | Minor changes |
| Test-MgBetaGroupSiteInformationProtectionSensitivityLabel | Minor changes |
| Test-MgBetaGroupSiteInformationProtectionSensitivityLabelSublabel | Minor changes |
| Test-MgBetaGroupSiteListContentTypePublished | Minor changes |
| Test-MgBetaUserDriveItemPermission | Minor changes |
| Test-MgBetaUserDriveListContentTypePublished | Minor changes |
| Test-MgBetaUserDriveRootPermission | Minor changes |
| Test-MgBetaUserInformationProtectionDataLossPreventionPolicy | Minor changes |
| Test-MgBetaUserInformationProtectionPolicyLabelApplication | Minor changes |
| Test-MgBetaUserInformationProtectionPolicyLabelClassificationResult | Minor changes |
| Test-MgBetaUserInformationProtectionPolicyLabelRemoval | Minor changes |
| Test-MgBetaUserInformationProtectionSensitivityLabel | Minor changes |
| Test-MgBetaUserInformationProtectionSensitivityLabelSublabel | Minor changes |
| Test-MgBetaUserSecurityInformationProtectionSensitivityLabelApplication | Minor changes |
| Test-MgBetaUserSecurityInformationProtectionSensitivityLabelClassificationResult | Minor changes |
| Test-MgBetaUserSecurityInformationProtectionSensitivityLabelRemoval | Minor changes |
| Undo-MgBetaUserChatMessageReplySoftDelete | Minor changes |
| Undo-MgBetaUserChatMessageSoftDelete | Minor changes |
| Unpublish-MgBetaGroupDriveListContentType | Minor changes |
| Unpublish-MgBetaGroupSiteContentType | Minor changes |
| Unpublish-MgBetaGroupSiteListContentType | Minor changes |
| Unpublish-MgBetaUserDriveListContentType | Minor changes |
| Update-MgBetaCommunicationCallContentSharingSession | Minor changes |
| Update-MgBetaDeviceAppManagement | Minor changes |
| Update-MgBetaDeviceAppManagementAndroidManagedAppProtectionApp | Minor changes |
| Update-MgBetaDeviceAppManagementAndroidManagedAppProtectionAssignment | Minor changes |
| Update-MgBetaDeviceAppManagementAndroidManagedAppProtectionDeploymentSummary | Minor changes |
| Update-MgBetaDeviceAppManagementDefaultManagedAppProtection | Minor changes |
| Update-MgBetaDeviceAppManagementDefaultManagedAppProtectionApp | Minor changes |
| Update-MgBetaDeviceAppManagementDefaultManagedAppProtectionDeploymentSummary | Minor changes |
| Update-MgBetaDeviceAppManagementManagedAppRegistrationOperation | Minor changes |
| Update-MgBetaDeviceAppManagementMdmWindowsInformationProtectionPolicyAssignment | Minor changes |
| Update-MgBetaDeviceAppManagementMdmWindowsInformationProtectionPolicyExemptAppLockerFile | Minor changes |
| Update-MgBetaDeviceAppManagementMdmWindowsInformationProtectionPolicyProtectedAppLockerFile | Minor changes |
| Update-MgBetaDeviceAppManagementTargetedManagedAppConfigurationApp | Minor changes |
| Update-MgBetaDeviceAppManagementTargetedManagedAppConfigurationAssignment | Minor changes |
| Update-MgBetaDeviceAppManagementTargetedManagedAppConfigurationDeploymentSummary | Minor changes |
| Update-MgBetaDeviceAppManagementTargetedManagedAppConfigurationSetting | Minor changes |
| Update-MgBetaDeviceAppManagementTask | Minor changes |
| Update-MgBetaDeviceAppManagementTaskStatus | Minor changes |
| Update-MgBetaDeviceAppManagementVppToken | Minor changes |
| Update-MgBetaDeviceAppManagementWindowsInformationProtectionDeviceRegistration | Minor changes |
| Update-MgBetaDeviceAppManagementWindowsInformationProtectionPolicy | Minor changes |
| Update-MgBetaDeviceAppManagementWindowsInformationProtectionPolicyAssignment | Minor changes |
| Update-MgBetaDeviceAppManagementWindowsInformationProtectionPolicyExemptAppLockerFile | Minor changes |
| Update-MgBetaDeviceAppManagementWindowsInformationProtectionPolicyProtectedAppLockerFile | Minor changes |
| Update-MgBetaDeviceAppManagementWindowsInformationProtectionWipeAction | Minor changes |
| Update-MgBetaDeviceAppManagementWindowsManagedAppProtection | Minor changes |
| Update-MgBetaDeviceAppManagementWindowsManagedAppProtectionApp | Minor changes |
| Update-MgBetaDeviceAppManagementWindowsManagedAppProtectionAssignment | Minor changes |
| Update-MgBetaDeviceAppManagementiOSManagedAppProtectionApp | Minor changes |
| Update-MgBetaDeviceAppManagementiOSManagedAppProtectionAssignment | Minor changes |
| Update-MgBetaDeviceAppManagementiOSManagedAppProtectionDeploymentSummary | Minor changes |
| Update-MgBetaDeviceManagementDepOnboardingSettingEnrollmentProfileDeviceProfileAssignment | Minor changes |
| Update-MgBetaDeviceManagementWindowsAutopilotDeviceIdentityDeviceProperty | Minor changes |
| Update-MgBetaDirectoryCertificateAuthorityCertificateBasedApplicationConfigurationTrustedCertificateAuthority | Minor changes |
| Update-MgBetaGroupTeamChannelMember | Minor changes |
| Update-MgBetaGroupTeamPrimaryChannelMember | Minor changes |
| Update-MgBetaSecurityCaseEdiscoveryCaseReviewSet | Minor changes |
| Update-MgBetaTeamChannelMember | Minor changes |
| Update-MgBetaTeamPrimaryChannelMember | Minor changes |
| Update-MgBetaTeamworkDeletedTeamChannelMember | Minor changes |
| Update-MgBetaUserChatInstalledApp | Minor changes |
| Update-MgBetaUserManagedDeviceWindowsDeviceAccount | Minor changes |

---
### Detailed Endpoint Changes

# Endpoint v1.0 Changes

## Statistics
- **Total endpoints**: 8163
- **Total endpoint changes**: 18
- **Added**: 0
- **Removed**: 0
- **Modified**: 18

### Added Endpoints (0)

No endpoints added.

### Removed Endpoints (0)

No endpoints removed.

### Modified Endpoints (18)

| Method | Path | Changes |
|--------|------|---------|
| GET | /deviceManagement/reports/microsoft.graph.getCachedReport | Minor changes |
| GET | /deviceManagement/reports/microsoft.graph.getCompliancePolicyNonComplianceReport | Minor changes |
| GET | /deviceManagement/reports/microsoft.graph.getCompliancePolicyNonComplianceSummaryReport | Minor changes |
| GET | /deviceManagement/reports/microsoft.graph.getComplianceSettingNonComplianceReport | Minor changes |
| GET | /deviceManagement/reports/microsoft.graph.getConfigurationPolicyNonComplianceReport | Minor changes |
| GET | /deviceManagement/reports/microsoft.graph.getConfigurationPolicyNonComplianceSummaryReport | Minor changes |
| GET | /deviceManagement/reports/microsoft.graph.getConfigurationSettingNonComplianceReport | Minor changes |
| GET | /deviceManagement/reports/microsoft.graph.getDeviceManagementIntentPerSettingContributingProfiles | Minor changes |
| GET | /deviceManagement/reports/microsoft.graph.getDeviceManagementIntentSettingsReport | Minor changes |
| GET | /deviceManagement/reports/microsoft.graph.getDeviceNonComplianceReport | Minor changes |
| GET | /deviceManagement/reports/microsoft.graph.getDevicesWithoutCompliancePolicyReport | Minor changes |
| GET | /deviceManagement/reports/microsoft.graph.getHistoricalReport | Minor changes |
| GET | /deviceManagement/reports/microsoft.graph.getNoncompliantDevicesAndSettingsReport | Minor changes |
| GET | /deviceManagement/reports/microsoft.graph.getPolicyNonComplianceMetadata | Minor changes |
| GET | /deviceManagement/reports/microsoft.graph.getPolicyNonComplianceReport | Minor changes |
| GET | /deviceManagement/reports/microsoft.graph.getPolicyNonComplianceSummaryReport | Minor changes |
| GET | /deviceManagement/reports/microsoft.graph.getReportFilters | Minor changes |
| GET | /deviceManagement/reports/microsoft.graph.getSettingNonComplianceReport | Minor changes |

# Endpoint beta Changes

## Statistics
- **Total endpoints**: 12975
- **Total endpoint changes**: 1
- **Added**: 0
- **Removed**: 0
- **Modified**: 1

### Added Endpoints (0)

No endpoints added.

### Removed Endpoints (0)

No endpoints removed.

### Modified Endpoints (1)

| Method | Path | Changes |
|--------|------|---------|
| GET | /administrativeUnits/{administrativeUnit-id}/microsoft.graph.checkMemberGroups | Minor changes |

---
### Detailed Scope Changes
# Permission Scope Changes

## Statistics
- **Total Scopes**: 351
- **Total Scope Changes**: 0
- **Added**: 0
- **Removed**: 0
- **Modified**: 0

## Added Scopes (0)
No scopes added.

## Removed Scopes (0)

No scopes removed.

## Modified Scopes (0)

No scopes modified.
