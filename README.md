# aamarpay

aamarpay is an online payment gateway service for Bangladesh. Committed to provide best payment experience online for business. Lowest fee and fast checkout will give you good experience of receiving payment online.

## How to use: 


We recommend install ``aamarpay`` through pip install .

.. code:: bash
```
$ pip install aamarpay
```

Output 
```
 from aamarpay.aamarpay import aamarPay
    pay = aamarPay(isSandbox=True,transactionAmount=600)
    paymentpath = pay.payment()
    return redirect(paymentpath)
    # Output: paymentpath output https://sandbox.aamarpay.com/paynow.php?track=AAM1636017211119390#
```

Find more details in [aamarPay](https://aamarpay.com/) 