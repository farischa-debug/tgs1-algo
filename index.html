from flask import Flask, render_template, request

app = Flask(__name__)

@app.route('/', methods=['GET', 'POST'])
def index():
    result = None

    if request.method == 'POST':
        harga = float(request.form['harga'])
        diskon = float(request.form['diskon'])
        tambahan = float(request.form['tambahan'])

        # Hitung diskon
        potongan = harga * (diskon / 100)
        harga_setelah_diskon = harga - potongan

        # Hitung setelah potongan tambahan
        total = harga_setelah_diskon - tambahan

        result = round(total, 2)

    return render_template('index.html', result=result)

if __name__ == '__main__':
    app.run(debug=True)
