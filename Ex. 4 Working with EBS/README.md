# Lab 4 – Working with Amazon Elastic Block Store (EBS)

## Author

* **Name**: HARI PRIYA M
* **Register Number**: 212224240047
* **Date of Submission**: 24-08-2026

---

## Objective

The objective of this experiment is to understand how Amazon Elastic Block Store (EBS) provides persistent block-level storage for EC2 instances. This lab focuses on creating and attaching an EBS volume, formatting and mounting it on an EC2 instance, storing data, and verifying data persistence after instance reboot.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing EC2 instance (Amazon Linux 2 preferred)
* Basic knowledge of Linux commands

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Amazon EBS
* SSH Client (Terminal / PuTTY)

---

## Tasks Performed

### Task 1: Explore Amazon EBS

Explore the Amazon EBS service through the EC2 dashboard. Observe different volume types such as General Purpose SSD (gp2/gp3), Provisioned IOPS SSD, Throughput Optimized HDD, and Cold HDD.

---

### Task 2: Create an EBS Volume

Create a new EBS volume in the same Availability Zone as the EC2 instance. Choose an appropriate size and volume type.

---

### Task 3: Attach EBS Volume to EC2 Instance

Attach the created EBS volume to the running EC2 instance as an additional block device.

---

### Task 4: Format the EBS Volume

Connect to the EC2 instance using SSH and format the attached volume with a file system (for example, ext4).

---

### Task 5: Mount the EBS Volume

Mount the formatted volume to a directory in the EC2 instance (for example, /data or /mnt/ebs).

---

### Task 6: Store Data in EBS Volume

Create files and directories inside the mounted EBS volume and store sample data.

---

### Task 7: Verify Data Persistence

Reboot the EC2 instance and verify that the data stored in the EBS volume is still available after reboot.

---

## Workflow (Student Explanation)

1. Created a 1 GiB EBS volume in the same Availability Zone as the EC2 instance and tagged it as **My Volume**.
2. Attached the EBS volume to the **Lab EC2 instance** and connected to it using **Session Manager**.
3. Formatted and mounted the volume as an **ext3 file system** at `/mnt/data-store` and configured automatic mounting.
4. Created a file on the volume, verified it, created an **EBS snapshot**, and deleted the original file.
5. Restored the snapshot to a new EBS volume, attached and mounted it, and verified that **file.txt** was recovered.

---

## Output Screenshots (Attach 3)

### Screenshot 1: EBS Volume Created

<img width="1897" height="1012" alt="Screenshot 2026-08-24 124700" src="https://github.com/user-attachments/assets/c239a1b8-2e66-4a56-b381-71fcc2fca3c3" />

---

### Screenshot 2: EBS Volume Attached to EC2

<img width="1917" height="1025" alt="Screenshot 2026-08-24 124930" src="https://github.com/user-attachments/assets/b4dde3b4-d672-4375-932e-3cbf100b0951" />

---

### Screenshot 3: Mounted Volume with Data
<img width="1917" height="1017" alt="Screenshot 2026-08-24 125948" src="https://github.com/user-attachments/assets/04e3cc89-1d51-4104-9e17-8e98a8d1d5a0" />
<br>
<img width="1917" height="1035" alt="Screenshot 2026-08-24 130043" src="https://github.com/user-attachments/assets/5387eec3-1bf0-4791-8049-700c23d67a89" />

---

## Result / Conclusion

This experiment demonstrated how Amazon EBS provides persistent storage for EC2 instances. By creating, attaching, formatting, and mounting an EBS volume, and by verifying data after reboot, the concept of durable block storage in the cloud was clearly understood.
