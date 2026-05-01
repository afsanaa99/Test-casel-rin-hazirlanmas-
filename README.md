# Test-casel-rin-hazirlanmas-
# Test Case Scenarios

---

## 1. Düzgün login üzrə yoxlanış

**Title:** Saytda düzgün login üzrə yoxlanış edilməsi  
**Description:** Login üzrə məlumatların daxil edilərək yoxlanması  

**Pre-conditions:** İstifadəçi uğurla login edib yeni hesab yaradır.

**Steps:**
1. Sayta daxil oldum  
   **Expected result:** Saytda məhsullar görünür
2. Sign in düyməsinə klik etdim  
   **Expected result:** İstifadəçi adı və şifrə tələb olunur
3. Yeni istifadəçi adı və şifrə daxil edilir  
   **Expected result:** Yeni hesab yaradılır

---

## 2. Məhsulların səbətə daxil olunması

**Title:** Məhsulların səbətə daxil olunması  
**Description:** Saytda məhsulların səbətə daxil edilərək yoxlanması  

**Pre-conditions:** Seçilmiş məhsul səbətə daxil edilir.

**Steps:**
1. Sayta daxil oldum  
   **Expected result:** Saytda məhsullar görünür
2. Echo Smart Plug klik etdim  
   **Expected result:** Məhsulun şəkli, qiyməti, stokları və Add to Cart görünür
3. Add to cart etdim  
   **Expected result:** Məhsul səbətə uğurla daxil oldu

---

## 3. Logout funksiyası

**Title:** Profildə logout funksiyasının yoxlanması  
**Description:** Logout funksiyasının düzgün işləməsinin yoxlanması  

**Pre-conditions:** İstifadəçi login edib.

**Steps:**
1. Sayta daxil oldum  
   **Expected result:** Saytda məhsullar görünür
2. Profil bölməsinə klik edilir  
   **Expected result:** Profil açılır
3. Login məlumatları daxil edilir  
   **Expected result:** Profil açılır
4. Logout klik edilir  
   **Expected result:** İstifadəçi sistemdən çıxır

---

## 4. Category bölməsi

**Title:** Category bölməsinin yoxlanması  
**Description:** Kateqoriyaların düzgün işləməsi  

**Pre-conditions:** Kateqoriyalar mövcuddur.

**Steps:**
1. Sayta daxil oldum  
   **Expected result:** Saytda məhsullar görünür
2. Headphones kateqoriyası seçilir  
   **Expected result:** Yalnız headphones məhsulları görünür
