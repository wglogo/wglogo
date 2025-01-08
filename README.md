<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pemesanan Desain Logo</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Pemesanan Desain Logo</h1>
        <p>Kami menyediakan layanan desain logo profesional dengan hasil terbaik.</p>
    </header>

    <main>
        <section id="order-form">
            <h2>Formulir Pemesanan</h2>
            <form id="logoForm">
                <label for="name">Nama:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="details">Detail Desain:</label>
                <textarea id="details" name="details" rows="5" required></textarea>

                <label for="package">Pilih Paket:</label>
                <select id="package" name="package" required>
                    <option value="basic">Paket Basic - Rp500.000</option>
                    <option value="premium">Paket Premium - Rp1.000.000</option>
                    <option value="exclusive">Paket Exclusive - Rp2.000.000</option>
                </select>

                <button type="submit">Kirim Pesanan</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Pemesanan Desain Logo. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
