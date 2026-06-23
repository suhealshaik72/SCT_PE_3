# SCT_PE_3

# Task 03 – Prompting for Task Automation

## Overview
This task focuses on using Prompt Engineering to automate repetitive tasks such as summarizing notes, extracting structured data, and converting information into different formats. The goal is to design a reliable prompt that can handle multiple inputs and consistently produce accurate outputs.

## Objective
- Learn how prompts can automate routine tasks.
- Create a structured prompt for data processing.
- Test the prompt with multiple input-output examples.
- Improve consistency and reliability of AI responses.

## Automation Task Example

### Prompt
Convert the following meeting notes into a structured summary with Action Items, Deadlines, and Responsible Persons.

### Input
- Complete project report by Friday.
- John will prepare the presentation.
- Team meeting scheduled for Monday.

### Output
**Action Items**
1. Complete project report
2. Prepare presentation

**Responsible Persons**
- John → Presentation

**Deadline**
- Friday → Project Report
- Monday → Team Meeting

## Input-Output Examples

### Example 1

**Input**
The workshop will be held on July 10. Students must register before July 5.

**Output**
```json
{
  "event": "Workshop",
  "event_date": "July 10",
  "registration_deadline": "July 5"
}
```

### Example 2

**Input**
Submit assignment by June 30. Presentation on July 2.

**Output**
```json
{
  "tasks": [
    {
      "task": "Submit Assignment",
      "deadline": "June 30"
    },
    {
      "task": "Presentation",
      "deadline": "July 2"
    }
  ]
}
```

### Example 3

**Input**
Meeting with client on Monday. Send proposal before Sunday.

**Output**
```json
{
  "meeting": "Client Meeting",
  "meeting_day": "Monday",
  "proposal_deadline": "Sunday"
}
```

## Process
1. Identify a repetitive task.
2. Design a clear prompt.
3. Test the prompt with multiple inputs.
4. Analyze consistency of outputs.
5. Refine the prompt if necessary.

## Learning Outcomes
- Understanding task automation using prompts.
- Creating reusable prompt templates.
- Extracting structured information from text.
- Improving prompt reliability through iteration.


## Reflection
During testing, the prompt was refined to improve consistency and output formatting. Clear instructions and structured examples helped the model generate reliable results across different inputs.

## Conclusion
This task demonstrates how Prompt Engineering can automate real-world tasks by converting unstructured information into organized and actionable outputs. Effective prompts improve accuracy, consistency, and efficiency.


## Author
Suheal Shaik  
MCA Student
