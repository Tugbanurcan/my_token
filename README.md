🪙 My Token – Tugba (MRB)

Bu proje, Solidity dilinde geliştirilmiş basit bir ERC-20 token sözleşmesini içermektedir.

OpenZeppelin kütüphanesi kullanılarak güvenli ve standartlara uygun bir yapı sağlanmıştır.

----------------------------
🔹Token Bilgileri

| Özellik             | Açıklama                    |
| ------------------- | --------------------------- |
| **Token Adı**       | merhaba                     |
| **Sembol**          | MRB                         |
| **Ondalık Basamak** | 2                           |
| **Toplam Arz**      | Deploy sırasında belirlenir |
| **Sözleşme Adı**    | `tugba`                     |

---------------------------------------------------
⚙️ Teknik Özellikler

OpenZeppelin’in resmi ERC20 standardı kullanılmıştır.

constructor fonksiyonu ile tokenlar deploy işlemi sırasında ilk dağıtımı yapan adrese mint edilir.

decimals() fonksiyonu override edilerek varsayılan 18 yerine 2 ondalık basamak kullanılacak şekilde ayarlanmıştır.

-----------------------------------------------------
🧱 Sözleşme Tanımı

contract tugba is ERC20

tugba: Kontratın adıdır. ERC20 standardını kalıtsal olarak alır.

ERC20: OpenZeppelin’in sağladığı, token transferi, bakiye görüntüleme gibi işlevleri içeren hazır ve güvenli bir yapı sunar.

---------------------------------------------------

💡 Projenin Amacı

* Bu proje, Ethereum ağı üzerinde çalışabilen temel bir token sistemi geliştirerek:

* Solidity ile kontrat yazmayı öğrenmek,

-> ERC-20 standardının işleyiş mantığını kavramak,

Blockchain geliştirme pratiği kazanmak

amaçlarıyla oluşturulmuştur.

🧪 Geliştirme Ortamı

Proje aşağıdaki ortamda geliştirilmiş ve test edilmiştir:

-> Remix IDE

-> Solidity ^0.8.0 sürümü

