# Pertanyaan yang Sering Diajukan

## Penyorotan Sintaks

VitePress menyediakan Penyorotan Sintaks yang didukung oleh [Shiki](https://github.com/shikijs/shiki), dengan fitur tambahan seperti penyorotan baris:

**Memasukkan**

````md
```js{4}
ekspor bawaan {
  data(){
    kembali {
      pesan: 'Disorot!'
    }
  }
}
```
````

**Keluaran**

```js{4}
ekspor bawaan {
  data(){
    kembali {
      pesan: 'Disorot!'
    }
  }
}
```

## Kontainer Khusus

**Memasukkan**

```md
::: info
Ini adalah kotak info.
:::

::: tip
Ini adalah tip.
:::

::: peringatan
Ini adalah peringatan.
:::

::: bahaya
Ini adalah peringatan yang berbahaya.
:::

::: detailnya
Ini adalah blok detail.
:::
```

**Keluaran**

::: info
Ini adalah kotak info.
:::

::: tip
Ini adalah tip.
:::

::: warning
Ini adalah peringatan.
:::

::: danger
Ini adalah peringatan yang berbahaya.
:::

::: details
Ini adalah blok detail.
:::

## Lagi

Lihat dokumentasi untuk [daftar lengkap ekstensi penurunan harga](https://vitepress.dev/guide/markdown).
