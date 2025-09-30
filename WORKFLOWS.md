# My n8n Workflows

## Workflow Descriptions

### Inventory.json
- **Purpose:** Reads Stock inventory details from excel sheet and return relevant datas
- **Trigger:** Webhook from Elevenlabs
- **Actions:** Collect details like Manufacture, Model, price, Year and others

### Raji - Calendar Booking.json
- **Purpose:** Books a meeting when customer asks
- **Trigger:** Webhook from Elevenlabs
- **Actions:** Books meeting with Name, Title, description. Send mail to users with notification and calendar invite. Also, books meeting in our own calendar (Company)

### Transcripts.json
- **Purpose:** Get conversation Transcripts everytime(every 1 hour) when user calls
- **Trigger:** Vapi-Schedule Trigger (as no webhook option in Vapi)
- **Actions:** Collect details like Name, phone number, called date if possible

### Supabase_RAG_AI_Agent (1).json
- **Purpose:** Get files from google drive, both new and updated files
- **Trigger:** Calling from Elevenlabs agent to ask for details
- **Actions:** Once connected, whenever we create new file or update an existing file, it automatically fetch them if needed.
 


## How to Use These Workflows

1. Download the JSON file you want
2. Open n8n
3. Go to Workflows
4. Click "Import from File"
5. Select the downloaded JSON file
6. Set up your credentials and test

## Last Updated: [03-09-25]
