# Mermaid Diagrams

```mermaid
---
title: Steps to Creating an Onyen
---
graph TD
a[[Go to onyen.unc.edu]]-->b[Select Create or Reactivate an onyen]
b-->c[Select 'I agree']
c-->d{Do you have a Guest ID?}
d-->|Yes|e[Select 'Yes' and sign in with your Guest ID email and password.]
d-->|No|f{Do you know your PID?}
f-->|Yes|g[Select 'No' and then fill out the form according to the information provided in your application.]
f-->|No|h[Select 'No' and then click on the link above the form that says 'Look up your PID here'.]
h-.->|Looked up PID|f
g-->i[Hit submit then select your Onyen and set your password.]
i-->j@{shape: rect , label: "Congrats you can now access your onyen"}
j-->k[Did you remember to enroll in Duo?]
k-->|Yes|l{You're all set!}
k-->|No|m[Select Manage Authentication Devices from the left column and follow the prompts to enroll.*If you're on a mobile device you may need to click on the three horizantal lines first to see that option.*]



style j fill:#33c1ff,stroke:#333,stroke-width:2px
style d fill:#33c1ff,stroke:#333,stroke-width:2px
style f fill:#33c1ff,stroke:#333,stroke-width:2px
style l fill:#33c1ff,stroke:#333,stroke-width:2px
classDef default fill:#90ceed,stroke:#333

```

### Description 
The Diagram above details a highly used process that I often come accross working. Students, faculty, and staff frequently have questions about creating or reactivating their onyen. For this particular process the steps are universal, meaning everyone uses them regardless of their status with the university. <br>

I placed important questions in the larger diamond shapes. These are questions regarding important piece of information that are absolutely necessary to complete the process.