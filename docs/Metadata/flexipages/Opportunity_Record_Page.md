---
layout: default
title: Opportunity_Record_Page
parent: flexipages
grand_parent: Metadata
---
# Metadata Type
flexipages


# Filename 
Opportunity_Record_Page


# Raw XML
```
<?xml version="1.0" encoding="UTF-8"?>
<FlexiPage xmlns="http://soap.sforce.com/2006/04/metadata">
    <flexiPageRegions>
        <itemInstances>
            <componentInstance>
                <componentInstanceProperties>
                    <name>collapsed</name>
                    <value>false</value>
                </componentInstanceProperties>
                <componentName>force:highlightsPanel</componentName>
                <identifier>force_highlightsPanel</identifier>
            </componentInstance>
        </itemInstances>
        <mode>Replace</mode>
        <name>header</name>
        <type>Region</type>
    </flexiPageRegions>
    <flexiPageRegions>
        <itemInstances>
            <componentInstance>
                <componentInstanceProperties>
                    <name>active</name>
                    <value>true</value>
                </componentInstanceProperties>
                <componentInstanceProperties>
                    <name>body</name>
                    <value>activityTabContent</value>
                </componentInstanceProperties>
                <componentInstanceProperties>
                    <name>title</name>
                    <value>Standard.Tab.activity</value>
                </componentInstanceProperties>
                <componentName>flexipage:tab</componentName>
                <identifier>activityTab</identifier>
            </componentInstance>
        </itemInstances>
        <itemInstances>
            <componentInstance>
                <componentInstanceProperties>
                    <name>body</name>
                    <value>feedTabContent</value>
                </componentInstanceProperties>
                <componentInstanceProperties>
                    <name>title</name>
                    <value>Standard.Tab.collaborate</value>
                </componentInstanceProperties>
                <componentName>flexipage:tab</componentName>
                <identifier>collaborateTab</identifier>
            </componentInstance>
        </itemInstances>
        <itemInstances>
            <componentInstance>
                <componentInstanceProperties>
                    <name>body</name>
                    <value>detailTabContent</value>
                </componentInstanceProperties>
                <componentInstanceProperties>
                    <name>title</name>
                    <value>Standard.Tab.detail</value>
                </componentInstanceProperties>
                <componentName>flexipage:tab</componentName>
                <identifier>detailTab</identifier>
            </componentInstance>
        </itemInstances>
        <mode>Replace</mode>
        <name>tabs</name>
        <type>Facet</type>
    </flexiPageRegions>
    <flexiPageRegions>
        <itemInstances>
            <componentInstance>
                <componentInstanceProperties>
                    <name>tabs</name>
                    <value>tabs</value>
                </componentInstanceProperties>
                <componentName>flexipage:tabset</componentName>
                <identifier>flexipage_tabset</identifier>
            </componentInstance>
        </itemInstances>
        <mode>Replace</mode>
        <name>main</name>
        <type>Region</type>
    </flexiPageRegions>
    <flexiPageRegions>
        <itemInstances>
            <componentInstance>
                <componentInstanceProperties>
                    <name>hideUpdateButton</name>
                    <value>false</value>
                </componentInstanceProperties>
                <componentName>runtime_sales_pathassistant:pathAssistant</componentName>
                <identifier>runtime_sales_pathassistant_pathAssistant</identifier>
            </componentInstance>
        </itemInstances>
        <mode>Replace</mode>
        <name>subheader</name>
        <type>Region</type>
    </flexiPageRegions>
    <flexiPageRegions>
        <itemInstances>
            <componentInstance>
                <componentName>runtime_sales_activities:activityPanel</componentName>
                <identifier>runtime_sales_activities_activityPanel</identifier>
            </componentInstance>
        </itemInstances>
        <mode>Replace</mode>
        <name>activityTabContent</name>
        <type>Facet</type>
    </flexiPageRegions>
    <flexiPageRegions>
        <itemInstances>
            <componentInstance>
                <componentName>forceChatter:recordFeedContainer</componentName>
                <identifier>forceChatter_recordFeedContainer</identifier>
            </componentInstance>
        </itemInstances>
        <mode>Replace</mode>
        <name>feedTabContent</name>
        <type>Facet</type>
    </flexiPageRegions>
    <flexiPageRegions>
        <itemInstances>
            <componentInstance>
                <componentName>force:detailPanel</componentName>
                <identifier>force_detailPanel</identifier>
            </componentInstance>
        </itemInstances>
        <mode>Replace</mode>
        <name>detailTabContent</name>
        <type>Facet</type>
    </flexiPageRegions>
    <flexiPageRegions>
        <itemInstances>
            <componentInstance>
                <componentName>force:relatedListQuickLinksContainer</componentName>
                <identifier>force_relatedListQuickLinksContainer</identifier>
            </componentInstance>
        </itemInstances>
        <itemInstances>
            <componentInstance>
                <componentName>force:relatedListContainer</componentName>
                <identifier>force_relatedListContainer</identifier>
            </componentInstance>
        </itemInstances>
        <mode>Replace</mode>
        <name>sidebar</name>
        <type>Region</type>
    </flexiPageRegions>
    <masterLabel>Opportunity Record Page</masterLabel>
    <parentFlexiPage>sfa__Opportunity_rec_L</parentFlexiPage>
    <sobjectType>Opportunity</sobjectType>
    <template>
        <name>flexipage:recordHomeWithSubheaderTemplateDesktop</name>
    </template>
    <type>RecordPage</type>
</FlexiPage>
```


# Last Modified


# Usage