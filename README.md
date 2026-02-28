# Hadoop HDFS & Java-Based Big Data Workflows

> Implemented Hadoop Distributed File System (HDFS) operations and Java-based file processing programs on a Hadoop cluster, demonstrating distributed data handling and big data infrastructure workflows.

**Author:** Amisha Farhana Shaik  
**Project Type:** Big Data Analytics | Hadoop | HDFS | Distributed Systems  

---

## Project Overview

This project demonstrates hands-on execution of Hadoop-based big data workflows using the CSUEB Hadoop cluster.

The objective was to:

- Execute HDFS file operations
- Compile and run Java programs within Hadoop
- Understand distributed file processing
- Validate file transfers between local disk and HDFS
- Work directly with Hadoop ecosystem components

---

## Environment

- Hadoop Cluster (CSUEB)
- HDFS (Hadoop Distributed File System)
- Java
- Linux command-line
- Hadoop 2.x ecosystem

---

## Part 1: FileSystemDoubleCat (Example 3-3)

### Objective

Display a file stored in HDFS to standard output twice using a Java-based Hadoop program.

### Workflow

1. Secure copy (scp) Java file from local machine to Hadoop server.
2. Copy Java file into HDFS using:
   - `hdfs dfs -copyFromLocal`
3. Set HADOOP_CLASSPATH environment variable.
4. Compile Java file with Hadoop dependencies.
5. Execute the Hadoop job on HDFS file input.
6. Display file contents from HDFS to terminal.

### What This Demonstrates

- Interaction between local filesystem and HDFS
- Setting up Hadoop classpaths
- Compiling Java programs against Hadoop libraries
- Running distributed file system operations via Hadoop CLI

---

## Part 2: FileCopyWithProgress (Example 3-4)

### Objective

Copy a file from local disk to HDFS while illustrating progress tracking during transfer.

### Workflow

1. Transfer Java file to Hadoop server.
2. Use `hdfs dfs -copyFromLocal` to move file into HDFS.
3. Compile Java file with Hadoop dependencies.
4. Execute Java program in Hadoop environment.
5. Validate file placement using HDFS directory listing.

### What This Demonstrates

- Distributed file copying with progress feedback
- HDFS directory structure management
- Validation of file storage in distributed system
- Cluster-side execution of Java applications

---

## Technical Skills Demonstrated

- Hadoop Distributed File System (HDFS)
- Big Data Cluster Navigation
- Linux Command-Line Operations
- SCP File Transfers
- Java + Hadoop Integration
- Environment Variable Configuration
- Hadoop CLI Execution
- Distributed Data Handling

---

## Key Learnings

- HDFS separates storage from computation.
- Java programs must be compiled against Hadoop libraries.
- Classpath configuration is critical for Hadoop execution.
- HDFS commands differ from local filesystem operations.
- Distributed systems require structured environment setup.

---

## Relevance to Big Data Analytics

This project builds foundational knowledge for:

- MapReduce programming
- Spark ecosystem workflows
- Distributed data engineering
- Large-scale data ingestion
- Production big data pipelines

---

This project demonstrates applications in:

Big Data Engineering | Hadoop Ecosystem | Distributed Systems | Data Infrastructure | Cluster Computing
