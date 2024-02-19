
from docxtpl import DocxTemplat
doc = DocxTemplate('report_template.docx')
subject = {
    'first_name': 'ridho',
    'last_name': 'Hafizd'    
    }
doc.render(subject)
doc.save('intel_report.docx')
