# MyPA (My Personal AI)

### 🚀 Project Pitch
MyPA is a personal AI assistant that helps users organize their day, manage tasks, and interact naturally using voice and text.  
It is designed to be simple, personal, and scalable for future use cases.  

> High-level architecture (MyPA):

[User: Web/Voice/Mobile] 
     ↕
[Frontend (React) — Web dashboard + chat UI]
     ↕
[API Gateway] -> [Lambda (fulfillment)] -> [DynamoDB]
                       ↕
                    [Bedrock] (reasoning / suggestions)
                       ↕
  [EventBridge/StepFunctions] -> [Lambda actions] -> [Google/Outlook Calendar / SES / SNS]
                       ↕
                    [Polly for voice replies] (optional)


### 🎯 Day 1 Deliverables
- ✅ Set up project folder (`MyPA`)  
- ✅ Initialize Git repository  
- ✅ Create README.md with project overview  
- ✅ Define high-level goals for the hackathon  
- ✅ Chose project name: **MyPA**  

### 📌 Next Steps
- Build a simple demo agent that responds to user input  
- Connect to AWS services for AI/voice integration  
- Prepare for Day 2 deliverables (basic working prototype)
