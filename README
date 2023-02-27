In this algorithm, the writer function waits for the semaphore before writing into the shared resource.
This ensures that only one writer can access the resource at a time.
The reader function acquires the mutex to update the read count and then checks if it is the first reader.
If it is, the function waits for the semaphore to ensure that no writers are accessing the resource.
The reader then releases the mutex and reads the shared resource.
After reading the shared resource, the reader acquires the mutex again to update the read count and checks if it is the last reader.
If it is, the function signals the semaphore to allow writers to access the resource.
The reader then releases the mutex.
