#### Create a Deployment
- name: app
- image: kulbhushanmayer/nodejs-app:v1
- containerPort: 4000
- label:
  - app: fe
#### Create a Service
- name: app
- port: 80
