# TechNova-Leads-Management

# TechNova Solutions: Lead Management Workflow

## Lead Scoring System

The lead scoring system assigns points to leads based on their responses to the following criteria:

### Company Size:
- 1-50 employees: 5 points
- 51-200 employees: 10 points
- 201-1000 employees: 15 points
- 1000+ employees: 20 points

### Annual Budget for SaaS Solutions:
- Less than $10,000: 5 points
- $10,000 - $50,000: 10 points
- $50,001 - $100,000: 15 points
- More than $100,000: 20 points

### Industry:
- Technology: 15 points
- Finance: 10 points
- Healthcare: 20 points
- Retail: 10 points
- Other: 5 points

### Urgency of Need:
- Immediate (within 1 month): 20 points
- Short-term (1-3 months): 15 points
- Medium-term (3-6 months): 10 points
- Long-term (6+ months): 5 points

## Workflow

1. **Trigger: New Form Submission in Google Forms**
   - Connect your Google Form to Zapier. This triggers when a new form submission is received.

2. **Action: Calculate Lead Score**
   - Use a Zapier Code by Zapier action to calculate the lead score based on the form responses.

3. **Action: Add Lead to Google Sheets**
   - Add a row to the Google Sheets spreadsheet with the lead details and their calculated score.

4. **Filter: Check Lead Score**
   - Use a filter to check if the lead score is greater than 70.

5. **Action for High Scoring Leads: Send Email via Gmail**
   - If the lead score is greater than 70, send a welcome email using the Gmail integration in Zapier.

6. **Action for Low Scoring Leads: Add to Nurturing Campaign Spreadsheet**
   - If the lead score is less than or equal to 70, add the lead to a different Google Sheets spreadsheet for nurturing campaigns.
