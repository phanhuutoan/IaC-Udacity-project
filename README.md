## Udacity-IaC-project

In this project, I will put our infra in 2 AZ.

### I. Project diagram

**Link: Lucid chart**
https://lucid.app/lucidchart/8e6e528d-ba03-4f78-9ccf-cf09810c7c25/edit?viewport_loc=-550%2C-166%2C2657%2C1245%2ClHqFiIN3g_.y&invitationId=inv_aee0863f-1af8-4fe9-8c40-b28df0b589f1
Images:
![Diagram](./images/architech.png)

### How to run

- Run: `chmod 400 ./updateStack.sh ./createStack.sh`

- To build network: `./updateStack.sh <Stack-name> ./configs/network.yml ./params/network-params.json`, the name is up to you.
