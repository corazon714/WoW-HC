# WoW Classic Hardcore — Genel Kurallar ve Mekanikler

**Versiyon:** Classic Era (1.14.x — Original HC) + Classic Fresh / Anniversary HC (1.15.x — 2024–2026)
**Son Güncelleme:** 2026-06-18
**Kapsam:** Blizzard official HC realmleri (her iki nesil) — kural farkları aşağıda işaretlenmiştir.
**Birincil Kaynak:** Wowhead Hardcore WoW Overview (Calamityhc), Blizzard HC FAQ, hardcore.wiki.gg

## Özet
WoW Classic Hardcore, tek bir basit kurala dayanır: **karakter ölünce karakter ölür.** Blizzard, 2023 Ağustos'ta Doomhowl/Bloodsail/Stitches gibi **Original HC** realmlerini açtı; 2024 Kasım'da 20th Anniversary ile **Classic Fresh HC** realmlerini başlattı (Defias Pillager NA, Skull Rock EU vb.). **İki realm setinin kural seti farklıdır** — özellikle "cheat death" mekanikleri (Bubble Hearth, Reincarnation, Soulstone). Bu fark hayati önemde — yanlış realmde yanlış strateji ölümle sonuçlanır.

---

## 0. Realm Tipleri ve Kural Farkları (ÇOK ÖNEMLİ)

> **HC** Bu tablo, **Anniversary / Classic Fresh HC** realmlerinde geçerli sıkılaştırılmış kuralları (Wowhead Overview, 2024-11 itibariyle) ve **Original HC** (2023) realmlerindeki ilk durumu karşılaştırır.

| Kural | Original HC (2023 — Bloodsail/Stitches) | Classic Fresh HC (2024+ — Defias Pillager/Skull Rock) |
|---|---|---|
| Karakter ölümü kalıcı | ✅ | ✅ |
| Resurrection (rez) tamamen disable | Sadece bazıları | ✅ **Tüm rez yasak — runback dahil** |
| **Paladin: Bubble + Hearthstone** | ✅ Çalışıyor | ❌ **YASAK** — immunity altındayken Hearthstone kullanılamaz |
| **Shaman: Reincarnation** | ✅ Çalışıyor (self-rez) | ❌ **DEVRE DIŞI** |
| **Warlock: Soulstone (self veya party)** | ✅ Çalışıyor | ❌ **DEVRE DIŞI** |
| Mail (kendi alt'a) | ✅ | ✅ |
| Mail (yabancıya) | ❌ | ❌ |
| Trade window | ❌ | ❌ |
| Auction House | ❌ | ❌ |
| Dungeon lockout | Tüm dungeon 24h | Tüm dungeon 24h |
| Level 60 + low-level dungeon mix | Açık | ❌ **YASAK** — 60'lar 60- ile aynı dungeon'a giremez |
| Yüksek level XP penalty (group) | Var | Var (SoM benzeri sıkılaştırma) |
| Battleground | Açık (sınırlı) | ❌ **Kapalı** (Premade **Wargames** açık — death kalıcı) |
| PvP flag (saldırı ile auto-flag) | Var | ❌ **Yok** — sadece `/pvp` ile manuel flag |
| **Duel to the Death** (DTTD) | `/makgora` komutu | `/duel` üzerinden DTTD (kazanan **String of Ears** buff alır) |
| Mob leash zone değişiminde reset | Standart | ✅ **Sıkı** — zone değişince mob agresini bırakır (high-lvl kiting low-lvl zone'a engellenir) |
| **Soul of Iron** buff sistemi | Yok | ✅ Chronicler NPC'leri (Ironforge/Undercity) |
| Realm progression (TBC'ye geçiş) | Mevcut (transfer ile) | ❌ **Classic Fresh HC TBC'ye ilerlemez** — transfer şart |

> **HC** Bu rehberin geri kalanı **iki realm setini de** kapsar; spec-class güncellemelerinde "Classic Fresh'te X devre dışı" notları açıkça verilmiştir.

---

---

## 1. Karakter Ölümü

### 1.1 Ölüm sonrası ne olur?
- Karakter "deceased" statüsüne geçer; **silinmez**, oynanamaz hale gelir.
- Karakter, ölü hâliyle başka bir Era (PvE/PvP) realme **ücretsiz** transfer edilebilir; orada normal karakter olarak yaşar. (Original HC: Bloodsail Buccaneers; Anniversary: kendi destination realmleri açıklanır.)
- Loot, mail (alt-stash), banktaki tüm itemler karakterle birlikte transfer olur.
- Karakter ölü hâlde realm'de **ghost olarak kalabilir** — chat, guild yönetimi yapılabilir; oynanamaz.

> **HC** **Classic Fresh HC'de** resurrection tamamen disable — yani Priest Rez, Druid Rebirth, runback, Soulstone, Reincarnation, hatta başka oyuncudan gelen rez de **çalışmaz**. Death = perma, kesin. **Original HC'de** bazı self-rez seçenekleri (Reincarnation, Soulstone) çalışıyordu; Classic Fresh ile bu kapatıldı.

> **HC** Karakter mezarlığa gitse de "Release Spirit" tuşuna basılırsa ölüm kalıcıdır. Casual ölüm de gerçek ölümdür.

### 1.2 Disconnect (DC) ölümü
- Sunucu çökmesi veya internet kesintisi nedeniyle ölünürse, **Blizzard bir kereye mahsus restore yapabilir** — ancak ekran görüntüsü ve combat log gerekir. Bu garanti değildir, GM keyfi. (Kaynak: Blizzard HC forum tartışmaları, 2023–2024)
- Pratik tavsiye: combat'taysa logout etme; logout bile 20 saniye sürer ve mob seni hala vurur. Her zaman güvenli zonede /camp.

### 1.3 Fall damage
- Fall damage ölüm sebeplerinin **#1 nedenidir**. (Kaynak: hardcore.wiki.gg ölüm istatistikleri, community veri toplama)
- Slow Fall (Mage), Levitate (Priest), Aspect of the Cheetah ve Feign Death glide tricklerini öğren.
- Engineering parachute cloak, Goblin Glider, Slow Fall scrolls hayatınızı kurtarır.

---

## 2. Sunucu-Genel Kuralları (Bannable)

Aşağıdaki davranışlar **karakterin geri restore edilmemesini** ve hesabın suspend edilmesini doğurabilir:

| Yasak | Açıklama |
|---|---|
| Trade window | Oyuncular arası direkt trade UI kapalıdır. Group loot dışında item el değiştirmez. |
| Mail (player → player) | Başka oyunculara mail gönderilemez. Sadece kendi alt karakterine mail atılabilir (aynı hesap, aynı realm/faction). |
| Auction House | AH tamamen devre dışıdır (HC realmlerinde UI yoktur). |
| World Buff farming with sacrifices | Onyxia/Nef/ZG world buff'larını alıp düşmeye izin var ama "buff slave" alt karakterlerin grindi yasak değil — sadece itemlerin paylaşımı yasak. |
| Layering exploit | Layer atlayarak mob/gather farmı yapma. |
| Group XP boost | Yüksek leveldan düşük levele "powerlevel" yapmak teknik olarak yasak değil ama XP penalty nedeniyle anlamsız (4 level fark → %50 XP, 6+ → %0). |
| Bug abuse / wall-walking | LoS exploit, ledge climbing, mob de-spawn trickleri GM tarafından soruşturulur. |
| Bot/multibox | Klasik realm kuralları geçerli; multibox software banlı. |

> **HC** Streamer ekosisteminde "Onlyfangs" (Asmongold), "Streamer Royale" gibi etkinliklerde uygulanan extra kurallar Blizzard kuralı değildir; o gruplara özeldir.

---

## 3. Grup ve Sosyal Mekanikler

### 3.1 Grup büyüklüğü ve raid kilidi
- Açık dünyada **maksimum 5 kişilik party**. (Kaynak: Blizzard HC FAQ)
- Karakter **raid grubuna katılamaz** (1-60 arası raid grubu tamamen kilitli — Onyxia/MC/BWL HC realm'inde ölü oyuncular için bile mevcut değil. Anniversary HC realmlerinde Naxx 1.15 patch'iyle Raid içeriği aktif edildi ama yine de PvP /makgora kuralları geçerli).
- Genel pratik: questlerin çoğu solo veya 3-5 kişi yapılır. 5+ kişi gerektiren elite questleri **skip** etmek yaygın.

### 3.2 Buff ve heal alma
- Yabancı oyuncudan buff/heal almak serbesttir.
- Yabancı bir Mage/Priest grup atmadan size food/water/buff verebilir.

### 3.3 Whisper, /yell, /say
- Tüm chat kanalları açık. Death broadcast tüm realm'e gider ("Player X has died in zone Y to mob Z, RIP").
- (Kaynak: Hardcore Death Log addon ve sunucu broadcast)

---

## 4. PvP Kuralları

### 4.1 Duel to the Death (Mak'gora) — HC'de tek meşru PvP
- **Original HC (2023):** `/makgora <name>` komutu ile spesifik HC duelo. Karşı taraf kabul → kazanan yaşar, kaybeden ölür.
- **Classic Fresh HC (2024+):** Standart `/duel` artık HC realmlerinde otomatik olarak **"Duel to the Death"** anlamına gelir (Wowhead Overview). Kazanan **String of Ears** trophy buff'ı alır — buff bar'da kaç düello kazandığını sayar.
  - **Level kuralları (Classic Fresh):** Karakter en az **Lvl 19** olmalı; level farkı belirli bir eşiği geçerse kazanan ear alamaz.
- Tüm buff'lar, consumable'lar, engineering trinketleri serbest. Kiting standardır.

### 4.2 Soul of Iron buff (Classic Fresh HC özel)
- Anniversary HC ile gelen yeni reward sistemi (Season of Mastery'den dönüş):
  - **Chronicler Fero** (Ironforge, Hall of Explorers arka kısmı) — Alliance.
  - **Chronicler Morta** (Undercity, Apothecarium, Herbalism trainer yakını) — Horde.
- Hiç ölmemiş karakter NPC'den **Soul of Iron** buff'ı talep edebilir. Tooltip: "Never Known Defeat".
- Spell olarak "Soul of Iron" /flex emote (taşa dönüşüm efekti).
- **Ölüm sonrası:** Soul of Iron buff fiziksel olarak corpse'tan dışarı atılır; karakter **Tarnished Soul** debuff'ı alır → tüm statlar **-%1**. Tekrar ölmek bu yüzdeyi büyütmez. NPC debuff'u temizleyebilir ama Soul of Iron geri verilmez.
- **Survivor unvanları** — Soul of Iron varken belirli bossları öldürmek ekstra title efekti ekler:
  - Survivor of the Firelord (Ragnaros)
  - Survivor of the Shadow Flame (Nefarian)
  - Survivor of the Old God (C'Thun)
  - Survivor of the Damned (Kel'Thuzad)

### 4.3 Wargames (Classic Fresh)
- Battlegrounds tamamen kapalı.
- Yerine **Premade Wargames** açık — taraflar manuel olarak ayarlar. Bu modda da **ölüm kalıcı** — Wargame içinde ölmek normal HC ölümü gibi sonuç verir. Dolayısıyla casual değil.

### 4.4 Açık dünya PvP
- PvP flag **manuel açılır**: `/pvp` komutu ile. 
- **Classic Fresh:** Düşman oyuncuya saldırmak otomatik flag açmaz (eski Vanilla mekaniğinin tersine).
- **Faction NPC'sine** saldırmak hâlâ flag açar (örn. Crossroads guard'larına saldırınca Horde'a karşı flaglanırsınız).

### 4.5 Griefing — Blizzard sıfır tolerans
- Quest NPC öldürme, kasıtlı oyuncu ölümüne sebep olma, non-consensual PvP flag açtırma, sahte rapor bombası → **hesap aksiyonu**. Wowhead Overview açıkça "firm anti-griefing stance" diyor.
- Sahte rapor (report bombing) da aynı şekilde cezalı.

---

## 5. Dungeon Kuralları (HC-spesifik!)

> **HC** Bu, en sık karıştırılan kuraldır. **Dikkatli oku.**

### 5.1 Dungeon Lockout
- Bir dungeon'a (instance) **girer girmez**, o dungeon **24 saatlik lockout**'a girer. (Kaynak: Wowhead HC Overview — "All dungeons have a 24 hour lockout timer, similar to Heroics")
- Bu lockout level-aralığına değil, dungeon'a özeldir. Yani Scarlet Monastery'nin Library, Armory, Cathedral, Graveyard wing'leri her biri ayrı lockout.
- Lockout süresi sona ermeden dungeon'a yeniden girilemez.

### 5.2 Yüksek Level XP Penalty
- Grupta bir oyuncu, mob'lardan **çok daha yüksek** seviyedeyse, mob'lar gruptaki diğer üyelere **çok az XP** verir (Season of Mastery benzeri kural). Yani 60 bir karakter, 40 mob'a vurursa 25 level karakter neredeyse hiç XP almaz.
- Bu, "yüksek level boost"u tamamen anlamsız hâle getirir.

### 5.3 Lvl 60 + Low-Level Mix YASAK (Classic Fresh)
- **Classic Fresh HC**: Level 60 oyuncular, **lvl 60'tan düşük** oyuncularla aynı dungeon'a giremez. Yani 60 bir karakter, dungeon içeriğinde 60-altı bir grup üyesiyle aynı instance'ta bulunamaz.
- Bu kural Wowhead Overview'de açıkça belirtilmiştir.
- **Original HC'de** bu kısıtlama vardı mı kesin değil — pratikte XP penalty zaten boost'u öldürdüğü için fark yaratmıyordu.

### 5.4 Wing kuralı (community yorum)
> **Not:** Topluluk arasında "her dungeon hayat boyu 1 kez" yanlış bilgisi yaygındır. Blizzard kuralı **24 saat lockout**, "lifetime lock" değil. Ancak bazı community challenge ve self-found rule setleri "lifetime 1 visit" izler.

### 5.5 Solo Dungeon Pratiği
- Hunter, Mage, Warlock, Druid belirli low-level dungeonları solo yapabilir.
- HC realm'de **lockout sebebiyle** dungeon'u tek seferde verimli bitirmek kritik. Yanlış dungeon'a yanlışlıkla girmek o lockout'u harcar.

### 5.6 Mob Leashing (Classic Fresh sıkılaştırması)
- "Creatures now leash and reset when leaving the area or zone they are engaged in." (Wowhead Overview)
- Bu, **yüksek level kiting'i low-level zone'a getirmeyi** engeller. Hunter pet kite'ı (questler için) yine çalışır.
- Detaylı leash timer / split pull mekaniği için bkz: [00-community-good-to-knows.md](00-community-good-to-knows.md)

---

## 6. Mail, Trade, Bank, Vendor

| Sistem | HC Durumu |
|---|---|
| Trade (player ↔ player) | **Kapalı** |
| Mail (aynı hesap, alt'lara) | **Açık** — kendi alt karakterinize mail gönderebilirsiniz; gold/item taşıma |
| Mail (yabancı oyuncuya) | **Kapalı** |
| Auction House | **Tamamen kapalı** (UI yok) |
| NPC vendor (al/sat) | **Açık** — limited stock vendor refresh kuralları normal |
| Group loot (Need/Greed/Master Loot) | **Açık** — gruptayken normal loot kuralları |
| Banker NPC (bank, guild bank) | **Açık** — guild bank özellikle solo guildler için alt-storage |

### 6.1 Self-found ekonomisi
- Tüm itemler kendi karakteriniz tarafından düşürülmüş, craftlanmış veya vendor'dan alınmış olmak zorunda (alt-stash hariç).
- Repair gold'u, food, water her zaman vendor'dan alınabilir. (Reagents'lar da vendor'dan açıktır, örn. Symbol of Kings, Death's Embrace.)

---

## 7. Profession ve Crafting (HC bağlamı)

- First Aid: **kritik öneme sahip**. Bandage cooldown'u her zaman senin için. Heroic Strike öncesi bandage at.
- Cooking: well-fed buff'u +5 stat. (Smoked Sagefish food'a 15-20 lvl için harika.)
- Engineering: parachute, dynamite, jumper cables, target dummy — HC'nin ÖNEMLİ profession'u.
- Alchemy: own consumes (Greater Healing Potion, Free Action Potion — fear/root immunity, **HC için altın**).
- Leatherworking/Tailoring: kendi armor'unu craftla; AH yok, sadece kendin için.

> **HC** Detaylar için bkz: [00-professions-ekonomi.md](00-professions-ekonomi.md)

---

## 8. Realm Nesilleri — Kısa Kılavuz

### 8.1 Original HC (2023 launch)
- **Realmler:** Bloodsail Buccaneers (EU), Doomhowl (NA), Stitches (NA), Skull Rock… (çeşitli)
- **Patch:** 1.14.4+ ile açıldı.
- **Karakter ölümü destinasyonu:** Bloodsail Buccaneers / paylarılan PvE realmleri (free transfer).
- **Cheat death mekanikleri (Bubble Hearth, Reincarnation, Soulstone):** Çalışıyor.
- **Raid:** Tam progression (MC → BWL → ZG → AQ → Naxx) zaman içinde açıldı.
- **TBC progression:** Mevcut — karakterler transfer ederek TBC Era'ya geçebildi.

### 8.2 Classic Fresh HC / Anniversary HC (2024-11+)
- **Realmler (NA):** Defias Pillager, Lava Lash, Skull Rock vb.; **EU:** Soulseeker, Doomhowl-EU vb.
- **Patch:** 1.15.x ile sıfırdan başladı — fresh economy, world buff race sıfırdan.
- **Sıkılaştırılmış kurallar:** Cheat death mekanikleri **devre dışı**, Soul of Iron buff sistemi **açık**, Lvl 60 + low-lvl dungeon mix **yasak**, PvP flag manuel.
- **Karakter ölüm destinasyonu:** Ayrı destination realmleri belirtildi (Blizzard duyurulu).
- **Raid:** Tier kademeli açılım — 1.15.1 launch'ta MC, sonra BWL… Anniversary timeline'ı. 1.15.3'te Naxx tier açıldı.
- **TBC progression:** ❌ **İlerlemez.** TBC oynamak isteyen oyuncular karakteri PvE/PvP realme transfer eder.

---

## 9. Genel Ölüm Verisi (community-aggregated)

> **Not:** Aşağıdaki yüzdeler Hardcore Death Log + Death Tracker addon istatistiklerinden derlenmiştir; kesinlik garantili değildir.

| Ölüm sebebi | Yaklaşık % |
|---|---|
| Mob over-pull (multiple add) | ~35% |
| Fall damage | ~15% |
| Elite mob (low level dolaşımda) | ~12% |
| Disconnect (DC) | ~8% |
| Patrol surprise | ~7% |
| Drowning | ~3% |
| Environmental (lava, fire, fatigue) | ~6% |
| PvP (Mak'gora) | ~2% |
| Other (boss, debuff, fear-into-pack) | ~12% |

---

## Kaynaklar
- **Wowhead Hardcore WoW Overview** (Calamityhc) — https://www.wowhead.com/classic/guide/hardcore-wow-overview
- **Wowhead Hardcore Tips & Tricks** — https://www.wowhead.com/classic/guide/tips-and-tricks-hardcore
- **Wowhead Hardcore Leveling Tier List** — https://www.wowhead.com/classic/guide/tier-lists/hardcore-leveling
- Blizzard official HC FAQ (forum sticky, Aug 2023)
- Blizzard 1.15 patch notes (Anniversary launch, 2024)
- hardcore.wiki.gg (community wiki, 2023–2026)
- Hardcore Death Log addon (TrueHorse) — community ölüm verisi
- r/HardcoreWoW wiki (FAQ, dangerous quests, addon list)
- HC OG community (pre-Blizzard) — Bobsmade, Trini, Defcamp & Melderon TV, OnlyFangs guild
