# ML-Studio-Preview

A graphical desktop app that enables codeless configuration of image based CNN models like EfficientNet, MobileNet, Inception, and ResNet, with a complementary server software consisting of Dockersised containers that train and store these models. 

***NOTE: This project is confidential and governed by [Prof. Ankur Miglani](https://iiti.irins.org/profile/113224) and [Prof. Pavan Kumar Kankar](https://iiti.irins.org/profile/93831). New releases will not be added until approval.**

This work is currently being documented, and should be completed by Jan 2026.

<details>
  <summary><h2>Home Page</h2></summary>

Shows buttons to create a new training set, and view previously trained models. Following is a list of previously created training sets that are stored in the app's local storage, ready to be sent to the second part of the software for training.
<img    alt="home" src="https://github.com/user-attachments/assets/1ccd4091-1721-4f82-97ae-41a911a85daa" />
</details>

<details>
  <summary><h2>Create New Traing Set Page</h2></summary>

The method has been broken down into four simple steps. Most of the graphical components are modular, that are generated from a Json-like configuation file which can be easily tweaked to suit the user's needs.
<img    alt="classifier" src="https://github.com/user-attachments/assets/7271e3c9-fcca-4c23-ace6-e7b4097e79b0" />

<img    alt="layoutspage" src="https://github.com/user-attachments/assets/4bd1306b-b82f-407d-80d0-a2c0123e441b" />

<img    alt="params" src="https://github.com/user-attachments/assets/f3b8d17c-18c4-4277-9b2f-52328b2ddd65" />

<img    alt="unsaved changes" src="https://github.com/user-attachments/assets/952fd90e-9183-4d1d-bf17-c360af6d85a9" />

<img    alt="import" src="https://github.com/user-attachments/assets/4f792b7e-20c3-4db1-9d49-db2b98e14cc4" />

<img    alt="split" src="https://github.com/user-attachments/assets/0c914918-4634-4f6c-8509-8a8cedf4f48c" />

<img    alt="name" src="https://github.com/user-attachments/assets/92f4f9e3-f626-47ab-8348-93d5d610c5e1" />

A simple script constantly checks for errors in the background, and warns the user if their configuration might be invalid.
<img    alt="errors" src="https://github.com/user-attachments/assets/5b5dc824-3e28-488f-abf5-b400a0631638" />

The training set, consisting of the images in their respective classes, along with a confiuragition file that is generated (that can be imported later in the app), are stored in a certain folder structure, and zipped, and stored in the app's local storage. This appears on the home page.
<img    alt="export" src="https://github.com/user-attachments/assets/47aa33dc-32b6-453a-8e04-ef664acc0aac" />

<img   alt="exported" src="https://github.com/user-attachments/assets/2cb298d4-7b1f-440c-b482-7468db3fb59f" />

The "View previous tasks" button on the home page navigates to this page, showing the list of previously trained models, that are retreived via HTTP from the second part of this app, that may run on a separate, more powerful computer.
<img   alt="servertasks" src="https://github.com/user-attachments/assets/bb9e5b6f-5427-4329-93e5-22b4983ef9e5" />
</details>

<details>
  <summary><h2>Settings Page</h2></summary>
  
One place to adjust configurations and manage the storage.
<img   alt="settings 1" src="https://github.com/user-attachments/assets/bbd13fdc-75b3-4315-8eec-a16e83df69a2" />

<img   alt="settings 2" src="https://github.com/user-attachments/assets/463e9f1e-2c8e-4b44-9e48-f62732bcd61e" />

<img    alt="delete" src="https://github.com/user-attachments/assets/227e6cee-b68f-481b-b1eb-4d6a57ac62ff" />

<img    alt="delete confirm" src="https://github.com/user-attachments/assets/c4e9db0e-21cb-402a-8d4f-4e9ddde9ff5f" />

<img  alt="clear cache" src="https://github.com/user-attachments/assets/999f3f4e-94fe-4dd2-91c8-b8c56dc1c921" />
</details>
