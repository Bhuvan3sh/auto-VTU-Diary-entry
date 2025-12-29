# BhuvaneshGPT

Automated Project Diary Entry System for VTU Internyet.

## Getting Started

1. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

2. **Configuration**: 
   Open `diary_automation.py` and enter your credentials: 
   - `user_mail`: Your email address in line 21
   - `user_passwd`: Your password in line 22

3. **Run the Automation**:
   ```bash
   python diary_automation.py
   ```

Prompt for ChatGPT for creating the excel for:
files requried: Project Synopsys or Project Report, Excel file templet is in the drectory, paset and overwrite the templet with the excle file containing the data.
```bash
Use this excel file template file to fill the details based on the attached synopsys. This record is used for the project diary entry in the VTU portal. Keep it consise and fill the entries for all the dates and fields. The hours keep it between 2-5 hours. Keep the each entry row unique and different from the previous one. And give output as the updated excel file with same name. Keep the dates intact as it is in the templet. Do not use generic words and sentences for the field entries. Keep each enty unique.
```
