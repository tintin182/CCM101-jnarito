# ☁️ Types of Cloud Storage

Cloud storage can be divided into three main types: **Block Storage, File Storage, and Object Storage**. Each type stores data differently and is suited for different needs.

| 💾 Storage Type        | 📝 Description                                                                                                                                | 🎯 Primary Use Case                                                                             | ☁️ Cloud Provider Example           |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | ----------------------------------- |
| **Block Storage**      | Stores data in small pieces called blocks. These blocks work like parts of a hard drive and can be attached to a computer or virtual machine. | Best for **virtual machines, databases, and applications** that need fast access to their data. | **AWS EBS (Elastic Block Store)**   |
| **📁 File Storage**    | Stores data as files inside folders and subfolders, similar to how files are organized on a regular computer.                                 | Best for **shared files and folders** that need to be accessed by different users or computers. | **AWS EFS (Elastic File System)**   |
| **🖼️ Object Storage** | Stores each file as an object together with information about the file. The objects are kept in a storage area called a bucket.               | Best for **photos, videos, backups, documents, and other large collections of files**.          | **AWS S3 (Simple Storage Service)** |

## 🖼️ Why Object Storage is the Best Choice

For the client's photo sharing application, **Object Storage is the best choice because it is made for storing large amounts of files such as photos and videos**. It can also grow as more users upload images, making it a good option for an application that may eventually store millions of photos.

## 📚 References

Amazon Web Services. (n.d.). *Amazon Elastic Block Store documentation*. [AWS EBS Documentation](https://docs.aws.amazon.com/ebs/?utm_source=chatgpt.com)

Amazon Web Services. (n.d.). *Amazon Elastic File System documentation*. [AWS EFS Documentation](https://docs.aws.amazon.com/efs/?utm_source=chatgpt.com)

Amazon Web Services. (n.d.). *Amazon Simple Storage Service documentation*. [AWS S3 Documentation](https://docs.aws.amazon.com/s3/?utm_source=chatgpt.com)

IBM. (2024). *What is cloud storage?* [IBM Cloud Storage Overview](https://www.ibm.com/think/topics/cloud-storage?utm_source=chatgpt.com)
