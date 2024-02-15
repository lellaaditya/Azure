# Different types of storage accounts

https://learn.microsoft.com/en-us/azure/storage/common/storage-account-overview

Types

1.Standard general-purpose v2	Blob

Storage (including Data Lake Storage1), Queue Storage, Table Storage, and Azure Files	

Locally redundant storage (LRS) / geo-redundant storage (GRS) / read-access geo-redundant storage (RA-GRS) Zone-redundant storage (ZRS) / geo-zone-redundant storage (GZRS) / read-access geo-zone-redundant storage (RA-GZRS)2	

Standard storage account type for blobs, file shares, queues, and tables. Recommended for most scenarios using Azure Storage. If you want support for network file system (NFS) in Azure Files, use the premium file shares account type.

2.Premium block blobs3	

Blob Storage (including Data Lake Storage1)	LRS ZRS2	

Premium storage account type for block blobs and append blobs. Recommended for scenarios with high transaction rates or that use smaller objects or require consistently low storage latency. Learn more about example workloads.

3.Premium block blobs3	

Blob Storage (including Data Lake Storage1)	LRS ZRS2	

Premium storage account type for block blobs and append blobs. Recommended for scenarios with high transaction rates or that use smaller objects or require consistently low storage latency. Learn more about example workloads.

4.Premium file shares3	

Azure Files	LRS ZRS2	

Premium storage account type for file shares only. Recommended for enterprise or high-performance scale applications. Use this account type if you want a storage account that supports both Server Message Block (SMB) and NFS file shares

5.Premium page blobs3	

Page blobs only	LRS ZRS2	

Premium storage account type for page blobs only. Learn more about page blobs and sample use cases.
