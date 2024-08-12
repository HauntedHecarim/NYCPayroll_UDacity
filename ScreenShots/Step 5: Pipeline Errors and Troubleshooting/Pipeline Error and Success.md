There was an error in the pipeline during Data Summary

![Pipeline Fail](https://github.com/user-attachments/assets/8031cce4-9956-42bd-b1bd-030420e3cd4d)

---

The error was saying that the Synapse database did not exist. 

Debug mode was entered. The connection to the resource was fine;

![DataFlow Debug Mode Connection Successful](https://github.com/user-attachments/assets/1ee70e89-4e1e-4eee-a0b5-699a9336db87)

The connection test to the linked resource was also successful;

![NYCPayroll_Summary_ConnectionSuccessful](https://github.com/user-attachments/assets/be54d686-927c-4dc9-8224-4419077d909d)

In the data aggregation while running debug mode it was possible to see the data

![Data Flow Dir Staging Successful Preview](https://github.com/user-attachments/assets/24ef933f-a52f-4fb0-a5fa-5dcfb65ef13f)

Additionally the dirstaging file creation was a success;

![Pipeline dirstaging Success](https://github.com/user-attachments/assets/014f14ed-d45b-412d-9977-cdce8a9379ce)

---

I am unsure why the pipeline is connecting to the synapse DB and I have run out of methods to test the connection. I hope submission of the other passing parts of the rubric are ok.

