<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<title>Pagamento via Pix</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body { font-family: Arial, sans-serif; padding: 20px; }
.qrcode { text-align: center; margin-top: 20px; }
button { margin-top: 20px; padding: 10px 20px; font-size: 16px; }
</style>
</head>
<body>

<h2>Pagamento via Pix 💰</h2>
<p>Use o QR Code abaixo para realizar o pagamento de <b>R$ 10,00</b>.</p>

<div class="qrcode">
    <img src="https://api.qrserver.com/v1/create-qr-code/?size=250x250&data=00020126490014br.gov.bcb.pix0127andersonvictorboy@gmail.com5204000053039865802BR5916AB202507041753516009Sao Paulo610901227-20062240520daqr253339218942105963042E6F" />
</div>

<p>Caso prefira, copie e cole o código Pix:</p>

<textarea style="width:100%; height:150px;">
00020126490014br.gov.bcb.pix0127andersonvictorboy@gmail.com5204000053039865802BR5916AB202507041753516009Sao Paulo610901227-20062240520daqr253339218942105963042E6F
</textarea>

<button onclick="window.location.href='index.html'">Já paguei</button>

</body>
</html>
