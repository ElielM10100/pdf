# pdf
eu criei um gerador de PDF em python, eu ultilizei muito o FORM


from reportlab.pdfgen import canvas
from reportlab.lib.pagesizes import A4

cnv = canvas.Canvas("meu_pdf.pdf", pagesize=A4)
cnv.drawString(72, 720, "Gerando PDF em Python com reportlab")
cnv.save()
