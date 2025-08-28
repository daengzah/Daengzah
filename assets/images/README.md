# 📸 Images Directory

## 🎯 Images yang Diperlukan

### 1. `profile-photo.jpg` - Logo Navigation
- **Ukuran**: 40x40px (akan di-resize otomatis)
- **Format**: JPG/JPEG
- **Deskripsi**: Foto profil untuk logo di navigation bar
- **Rasio**: 1:1 (square) - akan di-crop menjadi circle

### 2. `hero-photo.jpg` - Hero Image
- **Ukuran**: 300x300px (desktop), 250x250px (mobile)
- **Format**: JPG/JPEG
- **Deskripsi**: Foto utama di hero section
- **Rasio**: 1:1 (square) - akan di-crop menjadi circle

## 📋 Instruksi Penggunaan

### Cara Menambahkan Images:
1. **Siapkan foto** dengan ukuran minimal 300x300px
2. **Rename** menjadi `profile-photo.jpg` dan `hero-photo.jpg`
3. **Place** di folder `assets/images/`
4. **Refresh** browser untuk melihat hasil

### Tips untuk Images:
- **High Quality**: Gunakan foto dengan resolusi tinggi
- **Professional**: Pilih foto yang profesional dan formal
- **Good Lighting**: Pastikan pencahayaan yang baik
- **Neutral Background**: Background yang tidak terlalu ramai
- **Square Format**: Lebih baik jika foto sudah square

### Fallback Images:
Jika images tidak ditemukan, website akan tetap berfungsi dengan styling yang ada.

## 🔧 Customization

### Mengubah Ukuran:
Edit CSS variables di `assets/styles.css`:
```css
.nav__logo-img {
  width: 40px;  /* Ubah ukuran logo */
  height: 40px;
}

.hero__avatar {
  width: 300px;  /* Ubah ukuran hero image */
  height: 300px;
}
```

### Mengubah Border:
```css
.nav__logo-img {
  border: 2px solid var(--primary-color);  /* Ubah border logo */
}

.hero__avatar {
  border: 4px solid var(--primary-color);  /* Ubah border hero image */
}
```

## 📱 Responsive Images

Website sudah responsive untuk semua ukuran layar:
- **Mobile**: 250x250px
- **Tablet**: 300x300px  
- **Desktop**: 350x350px

---

**Note**: Pastikan images yang digunakan memiliki lisensi yang sesuai atau adalah foto pribadi Anda sendiri.
