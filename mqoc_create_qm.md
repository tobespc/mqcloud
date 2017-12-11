---
copyright:
  years: 2017
lastupdated: "2017-12-6"
---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}

# Creating a queue manager
{: #mqoc_create_qm}

A guide to creating a new queue manager.
{:shortdesc}

In this task, you do the following:
1. Launch MQ on IBM Cloud.
2. Create a queue manager.

---

## Prerequisites
{: #prereq_mqoc_create_qm}

None.

---

## Launching MQ on IBM Cloud
{: #launch_mqoc_create_qm}

Note that if you're already in the service instance view, you can skip the following steps and continue with **Creating a queue manager**.

1. Log in to the IBM Cloud console (ensuring that your region is set to **us-south**).
2. Click **Catalog**.
3. Scroll to the end of the catalog and click **IBM Cloud Experimental Services**.
4. Navigate to **Platform** > **Integrate** and click **MQ**.
5. Type in a service name.
6. Click **Create**.

You are now presented with a view of your service instance from where you will be able to view and manage your queue managers once they have been created.

## Creating a queue manager
{: #crqm_mqoc_create_qm}

Starting from the 'Manage' menu option within the service instance view:

1. Click **Create**.
2. Choose a unique name for your new queue manager.
 * Please ensure that your queue manager name only contains characters from the following set: a-z, A-Z, 0-9, underscore and period.
3. Choose a display name, something that you can quickly identify your queue manager with.
4. Choose a region (currently limited to 'US-South').
5. Choose a plan (currently limited to 'Trial').
6. Click **Create**.

A record of your new queue manager will appear with a status of `Deploying`.

The status of your new queue manager will automatically refresh every 30 seconds.

When you see that your queue manager has a status of `Running`, it's ready to be configured for use.

---

## Conclusion
{: #conc_mqoc_create_qm}

You have successfully launched MQ on IBM Cloud and created a queue manager.

---

## Next step
{: #next_mqoc_create_qm}

Administer your new queue manager, using one of the [queue manager administration options](/docs/services/mqcloud/mqoc_admin_qm.html)