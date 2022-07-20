import barcode from powershell
create a class
import barcode
//using ean13
>>> hr=barcode.get_barcode_class('ean13')
>>> Hr=hr('1234567891012')
//name of the product
>>> qr=Hr.save('123')
//rewritting the svg file to your real img
 from barcode.writer import ImageWriter
hr=barcode.get_barcode_class('code39')
 rr=Hr.save('1234')