import pytesseract
pytesseract.pytesseract.tesseract_cmd = 'C:\\Program Files\\Tesseract-OCR\\tesseract.exe'
# pytesseract.image_to_string(img.open("captcha.png"))
# print(pytesseract.image_to_string('captcha.png'))
# print(pytesseract.image_to_string('paymentCaptcha.png'))
print(pytesseract.image_to_string('cap1.jpg'))
# print(pytesseract.image_to_string('images.png') )
