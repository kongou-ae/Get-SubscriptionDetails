# Get-SubscriptionDetails

## Description
Get-SubscriptionDetails collect your Azure Subscription's details.

## Usage
1. Run PowerShell console
2. Run GSD script (ex. Get-SubscriptionDetails -SubscriptionID 1b30dfe1-c2b7-468d-a5cd-b0662c94ec2f)
3. login to azure  (ASM and ARM)
4. wait for a while

## Features
* Collect ASM Resource Information
    * Compute
        * ASM Windows VM
        * ASM Linux VM
    * Storage
        * ASM Storage Account
        * ASM VM Disk
        * ASM OS Image
    * Network
        * ASM DNS Server
        * ASM Local Network Sites
        * ASM Virtual Network Sites
        * ASM Virtual Network Gateway
        
* Collect ARM Resource Information
    * Compute
        * ARM Windows VM
        * ARM Linux VM
    * Storage
        * ARM Storage Account
        * ARM VM Disk
    * Network
        * ARM Virtual Network
        * ARM Virtual Network Gateway
        * ARM Network Interface
        * ARM Public IP Address
        * ARM Local Network Gateway
        * ARM Local Network Sites

## Requirements
This script need Latest version of [Azure PowerShell module](http://aka.ms/webpi-azps). 

How to install and configure Azure PowerShell (Doc: [English](https://azure.microsoft.com/en-us/documentation/articles/powershell-install-configure/) | [Japanese](https://azure.microsoft.com/ja-jp/documentation/articles/powershell-install-configure/))

## Lincense
Copyright (c) 2016 Syuhei Uda
Released under the [MIT license](http://opensource.org/licenses/mit-license.php )

## Release Notes
2016/04/24 Ver.0.8.0 (Preview Release)