---
outline: deep
---

# Contoh API Runtime

Halaman ini menunjukkan penggunaan beberapa API runtime yang disediakan oleh VitePress.

API `useData()` utama dapat digunakan untuk mengakses data situs, tema, dan halaman untuk halaman saat ini. Ia berfungsi di file `.md` dan `.vue`:

```md
<script setup>
import { useData } from 'vitepress';

const { theme, page, frontmatter } = useData();
</script>

## Hasil

### Data Tema
<pre>{{ theme }}</pre>

### Data Halaman
<pre>{{ page }}</pre>

### Halaman Frontmatter
<pre>{{ frontmatter }}</pre>
```

<script setup>
import { useData } from 'vitepress';

const { site, theme, page, frontmatter } = useData();
</script>

## Hasil

### Data Tema
<pre>{{ theme }}</pre>

### Data Halaman
<pre>{{ page }}</pre>

### Halaman Frontmatter
<pre>{{ frontmatter }}</pre>

## Lagi

Lihat dokumentasi untuk [daftar lengkap API runtime](https://vitepress.dev/reference/runtime-api#usedata).
