---
layout: default
title: Contact
parent: duplicateRules
grand_parent: Metadata
---
# Metadata Type
duplicateRules


# Filename 
Contact


# Raw XML
```
<?xml version="1.0" encoding="UTF-8"?>
<DuplicateRule xmlns="http://soap.sforce.com/2006/04/metadata" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
    <actionOnInsert>Allow</actionOnInsert>
    <actionOnUpdate>Allow</actionOnUpdate>
    <alertText>You&apos;re creating a duplicate record. We recommend you use an existing record instead.</alertText>
    <description>Duplicate Rule for Contacts using the Standard Contact Matching Rule</description>
    <duplicateRuleFilter xsi:nil="true"/>
    <duplicateRuleMatchRules>
        <matchRuleSObjectType>Contact</matchRuleSObjectType>
        <matchingRule>Standard_Contact_Match_Rule_v1_1</matchingRule>
        <objectMapping xsi:nil="true"/>
    </duplicateRuleMatchRules>
    <duplicateRuleMatchRules>
        <matchRuleSObjectType>Lead</matchRuleSObjectType>
        <matchingRule>Standard_Lead_Match_Rule_v1_0</matchingRule>
        <objectMapping>
            <inputObject>Contact</inputObject>
            <mappingFields>
                <inputField>MailingCity</inputField>
                <outputField>City</outputField>
            </mappingFields>
            <mappingFields>
                <inputField>AccountId</inputField>
                <outputField>Company</outputField>
            </mappingFields>
            <mappingFields>
                <inputField>Email</inputField>
                <outputField>Email</outputField>
            </mappingFields>
            <mappingFields>
                <inputField>FirstName</inputField>
                <outputField>FirstName</outputField>
            </mappingFields>
            <mappingFields>
                <inputField>LastName</inputField>
                <outputField>LastName</outputField>
            </mappingFields>
            <mappingFields>
                <inputField>Phone</inputField>
                <outputField>Phone</outputField>
            </mappingFields>
            <mappingFields>
                <inputField>MailingStreet</inputField>
                <outputField>Street</outputField>
            </mappingFields>
            <mappingFields>
                <inputField>Title</inputField>
                <outputField>Title</outputField>
            </mappingFields>
            <mappingFields>
                <inputField>MailingPostalCode</inputField>
                <outputField>PostalCode</outputField>
            </mappingFields>
            <outputObject>Lead</outputObject>
        </objectMapping>
    </duplicateRuleMatchRules>
    <isActive>false</isActive>
    <masterLabel>Standard Contact Duplicate Rule</masterLabel>
    <operationsOnInsert>Alert</operationsOnInsert>
    <operationsOnInsert>Report</operationsOnInsert>
    <operationsOnUpdate>Report</operationsOnUpdate>
    <securityOption>EnforceSharingRules</securityOption>
    <sortOrder>1</sortOrder>
</DuplicateRule>
```


# Last Modified


# Usage