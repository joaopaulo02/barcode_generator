# ▌│█║▌║▌║ Barcode Genetaror ▌│█║▌║▌║
## Description 📔
### From a pre-defined JSON input, generate a barcode! (using Python and other tools)
## Technologies used 💻:
- [Flask](https://flask.palletsprojects.com/en/3.0.x/)
- [python-barcode](https://python-barcode.readthedocs.io/en/stable/)
- [Pylint](https://pylint.readthedocs.io/en/stable/)
- [pre-commit](https://pre-commit.com/)
- [Pytest](https://docs.pytest.org/en/7.1.x/contents.html)
## How to use 🤷‍♂️:
1. Create a JSON structure in the input with the pre-defined "product_code" key, following the example:
> ⚠️ OBS: The value of the "product_code" key MUST be a string!
<img src="https://media.discordapp.net/attachments/733037083941142681/1206002359537373194/barcode-gen-ex1.png?ex=65da6c38&is=65c7f738&hm=17bba1682c8607f95daac1bd3011fb8ef25ab312cc8905869dee871635239c86&=&format=webp&quality=lossless&width=380&height=380">
2. After doing this, the Barcode .png file will be generated as the output!
<img src="https://media.discordapp.net/attachments/733037083941142681/1206002359952474142/barcode-gen-ex2.png?ex=65da6c39&is=65c7f739&hm=7aff707633ba4c3b52b9212d8f77c42a6f445b280eb43ea1a01124f16c27c7e2&=&format=webp&quality=lossless">
