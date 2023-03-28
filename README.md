# OpenShift RWX Storage via AWS EFS

OpenShift, when installed on AWS, comes with dynamic EBS-backed persistent
storage. EBS only supports `ReadWriteOnce` (RWO) access mode. For applications
that require `ReadWriteMany` (RWX), AWS EFS can be used.
