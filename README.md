# 2025 Azure AD Lab – Two Domain Controllers Setup

## Goal
Set up two domain controllers in Azure in a virtual network, with working AD, DNS, and replication.

---

## Loom Recordings

### Part 1 – Initial Setup (Resource Group, VNet, DC1)
> _Note: This recording shows only the browser tab, not the entire screen._ 

[![Watch Part 1](https://cdn.loom.com/sessions/thumbnails/589ef51df3874eb7bb7bac3fbea1f47f-with-play.jpg)](https://www.loom.com/share/589ef51df3874eb7bb7bac3fbea1f47f)

---

### Part 2 – DC2 Setup, Replication, and Final Verification
> _Note: This recording shows the full screen, including RDP sessions._

[Watch Part 2 on Loom] https://www.loom.com/share/30144ad2c52a494ea33d4d0fe8b251dc?sid=dac1e621-a3c6-4add-94d8-e9c4ebd7a58d
---

## Lab Summary

This lab covers:

-Creating an Azure Resource Group and Virtual Network

-Deploying two Windows Server 2019 domain controllers (DC1 & DC2) in Azure VMs

Installing and configuring Active Directory Domain Services (AD DS)

-Setting up a new Active Directory Forest (myazurelab.com)

-Promoting DC1 as the first domain controller and creating SYSVOL and NTDS folders on a separate data drive

-Adding DC2 as an additional domain controller in the existing forest and ensuring replication

-Configuring DNS on both DCs with static private IPs and custom DNS settings in the virtual network

-Verifying Active Directory replication by creating and syncing test users between DC1 and DC2

-Configuring Active Directory Sites and Services, including subnet mapping

-Ensuring SYSVOL replication and domain controller synchronization

-Understanding core AD concepts like domain controllers, forest, replication, DNS integration, and subnet topology


## Result

-A fully functional Active Directory Forest (myazurelab.com)

-Two domain controllers (DC1 & DC2) with proper SYSVOL and NTDS data storage

-DNS properly configured and replicating within Azure Virtual Network

-Active Directory replication verified between domain controllers

-Active Directory subnet mapping set up to support site-aware services

---

