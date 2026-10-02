# MyTech сайт + QPay
1. `cd mytech-site`
2. Туршилт (sandbox):
   QPAY_USERNAME=... QPAY_PASSWORD=... QPAY_INVOICE_CODE=... PUBLIC_URL=https://таны-домэйн node server.js
3. Бодит болгохдоо `QPAY_BASE=https://merchant.qpay.mn/v2` нэмнэ.
4. Нээх: http://localhost:3000
Захиалга `orders.json`-д хадгалагдана. QPay callback нь PUBLIC_URL (интернэтээс хандах боломжтой хаяг) шаардана.
