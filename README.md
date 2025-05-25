# Lead Generator System

This is the main repository for the **Lead Generator** project.

- [Frontend Repository](https://github.com/Rupeshchand/Lead-Generation-client) 
- [Backend Repository](https://github.com/Rupeshchand/Lead-Generation-server)

Both are included as Git submodules in this monorepo.

**Demo URL Frontend**: [https://lead-generation-coral.vercel.app/]
**Backend**: [https://lead-generation-server.onrender.com]


## Project Structure

```plaintext
Lead Generation/
├── Lead-Generation-client/     # React.js frontend app (submodule)
├── Lead-Generation-server/     # Node.js/Express backend service (submodule)
├── .gitmodules                 # Git submodule config
├── README.md                   # This file
```

## Video Walkthorugh Link

    [https://www.loom.com/share/263aa3fbeaf5474c84829c9b4a6356b4]


## How to Setup Locally

```bash
# 1. Clone the main repository along with submodules
git clone --recurse-submodules https://github.com/Rupeshchand/Lead-Generation-System.git

cd Lead Generation

# 2. Install frontend dependencies
cd Lead-Generation-client
npm install
npm run dev  # Or your preferred React start command

# 3. Install backend dependencies
cd Lead-Generation-server
npm install
npm start  
```

## Setup and Run the project locally link

    [https://www.loom.com/share/7629eb0d03614e57a649ce39ed2c15aa]
    

## Webhook Integration with n8n

This project is integrated with **n8n** to automate lead processing to send 

- **n8n Webhook URL**: `https://rupesh19.app.n8n.cloud/workflow/FmQW4OC7P87p9R1V`
-  Once a form is submitted on the frontend, data is sent to the backend which triggers this n8n webhook.

## Note

Each folder (`Lead-Generation-client` and `Lead-Generation-server`) includes its own `README.md` with setup instructions and environment variables.

## Author

- LinkedIn: [Rupeshchand](https://www.linkedin.com/in/rupesh-chand-96223a190)
- GitHub: [@Rupeshchand](https://github.com/Rupeshchand)