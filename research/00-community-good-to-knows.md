# WoW Classic Hardcore — Community Good-to-Knows

**Versiyon:** Classic Era 1.15.x / Anniversary HC (Classic Fresh)
**Son Güncelleme:** 2026-06-18
**Kapsam:** Resmi rehberlerde olmayan, community'nin keşfettiği ve denenmiş hayat kurtarıcı tüyolar. Hardcore Discord, r/HardcoreWoW, OnlyFangs, Bobsmade, Defcamp & Melderon TV, Asmongold/Sodapoppin streamleri ve HC OG (pre-Blizzard) yıllardan derlenmiştir.
**Birincil Kaynak:** Wowhead Hardcore Tips & Tricks (Calamityhc) — https://www.wowhead.com/classic/guide/tips-and-tricks-hardcore

## Özet
Resmi guidelerin atladığı detaylar bazen hayat kurtarıyor. Bu dosya 100+ küçük tüyo içeriyor — combat tricks, escape mechanics, leash/thrash/daze görünmez mekanikleri, vendor saatleri, gizli quest reward'ları, sosyal dinamikler.

---

## 0. Wowhead'in "Görünmez" Game Mechanics — HC'nin Bilim Tarafı

Bu bölüm Wowhead'in resmi HC Tips & Tricks rehberinden çıkarılmış mekanik detaylarıdır. Çoğu oyuncu yıllarca farklı zannederek oynar; bu değerleri ezbere bilmek HC'de **kritik fark** yaratır.

### 0.1 Mob Leash Timer (süre bazında — mesafe bazında DEĞİL)
Çoğu oyuncunun yanlış bildiği: leash mesafeye değil, **süreye** bağlıdır ve mob levelına göre değişir.

| Mob Level Range | Leash Duration |
|---|---|
| 1-29 | **11 sn** |
| 30-39 | **12 sn** |
| 40-44 | **13 sn** |
| 45-49 | **14 sn** |
| 50-60 | **15 sn** |

**İstisna:** Mob spawn noktasının **15-30 yard** çevresinde leash hiç kırılmaz. Spawn'a yakın dönüşlü kite'lar işe yaramaz.

### 0.2 Leash'i UZATAN ve UZATMAYAN aksiyonlar

| Leash UZATIR | Leash UZATMAZ |
|---|---|
| Successful melee attack | Dodge / Miss / Parry |
| DoT spell apply (Corruption, Serpent Sting vs.) | DoT tick damage |
| Damageless spells (Curse of Tongues vs.) | Spell reflect |
| Resist / Immune | Thorns / Retribution Aura passives |

**Özetle:** Mob'a aktif/iradi olarak "vurduğunda" leash uzar. Pasif damage (Thorns, RetAura, DoT tick) sayılmaz. Escape ederken **ESC tuşuna basarak auto-attack'ı kes** — leash timer başlar.

### 0.3 Split Pulling Mekaniği
Mob'a vurduğunda yanındaki mob'lara "cry for help" gönderir → leash zinciri oluşur (birinin leash'i uzayan grup boyunca herkesin leash'i uzar).

**Bypass:** Tek seferde AoE ile birden çok mob'a vurmak. AoE her birine ayrı leash açar — cry for help çalışmaz.

AoE'si olmayan class'lar için alternatif:
- **M73 Frag Grenade** (Engineering quest item).
- **Flash Bundle** (quest reward).
- **Iron Grenade** (Engineering crafted).

Split pull tamamlandıktan sonra istediğin focus'ı öldür; geri kalan mob'ların leash'i 11-15 sn içinde kırılır ve reset olurlar.

### 0.4 Thrash (Görünmez Tehlike)
- **Thrash**, Windfury Weapon benzeri pasif yetenek — mob extra attack vurur.
- **Buff/aura ikonu YOKTUR** — oyuncu görerek tespit edemez.
- **Stack edebilir!** Kite ederken mob seni vuramıyorsa Thrash pool olur; sonra tek pencerede **5–7 swing** savaşabilir.
- **Çözüm:** 
  1. **Classic Bestiary** addon — Thrash bilen mob'ları etiketler.
  2. Kite ederken düzenli aralıklarla mob'un sana ulaşmasına izin ver (Thrash stack birikmesin).

### 0.5 Daze Mekaniği
- **Daze** sadece **sırtının** mob'a dönük olduğu durumda proc olur.
- Backpedal (S tuşu) **kalıcı yavaşlatma** uygular — kaçış için ASLA backpedal yapma.
- **Çözüm:** Strafe (Q/E veya keybinds) ile yüzün kısmen mob'a dönük — backbone dönmüyor, daze proc olmuyor.
- **Strafe-jump:** Zıpla + sağ mouse butonu ile karakteri mob'a doğru döndür (havadayken vurulursan ön cepheden vurulursun, daze yok); sonra geri dön ve yönünü sürdür. Mob seni yenebilir mesafe içindeyken bu pattern'i tekrarla.

### 0.6 Kamera Maximum Zoom (Wowhead resmi macro)
Default zoom yetersiz — mob'ları önceden görmek HC'de hayat kurtarır.

```
/console cameraDistanceMaxZoomFactor 3.9
```

**Leatrix Plus** addon'unda Settings → Maximum Camera Distance toggle ile aynı işlem.

### 0.7 Enemy Nameplates (Always Show)
Interface Settings → Names → **Always Show Nameplates**: Düşman mob isimleri terrain arkasından bile görünür. "Sürpriz pull" ölümlerini çok azaltır.

### 0.8 Wowhead'in Top 10 HC Tip Kısa Liste
1. **Yesıl (green) quest yap** — yellow/orange daha zor (hit chance dezavantajı).
2. **Use it or lose it** — sticky glue, healing potion vb. "sakla" deme; ölmek sandıkta bırakmaktan iyi.
3. **Weapon upgrade'i yolundan çıkarak yap** — hızlı fight = az risk.
4. **Camera zoom out 3.9**.
5. **Caster mob'lar ölümcül** — Defias Pillager #1 oyuncu öldüren. **LoS abuse**.
6. **Enemy nameplates açık**.
7. **Spell training parasını akıllı harca** — lvl 40 mount için tasarruf et. Örn. Frost Nova'nın yüksek rankına gerek var mı?
8. **Bag al** — 5s pouch, 2 vendor trip sonra kâr.
9. **Kaçış rotası her zaman planlı** — mob respawn, diğer oyuncu, underestimate — hep beklenmedik.
10. **Cave'ler ölümcül** — cave = kaçış rotasının zıttı. Bol hazırlık + Hearthstone hazir.

---

## 1. Combat & Escape Mekanikleri

### 1.1 Hearthstone interrupt'a karşı
- Hearthstone cast bar (10 saniye) silence/kick'lenebilir ama çoğu mob caster değildir.
- **Çözüm:** HS'i basmadan önce 1 step away → Frost Nova / Stun / Snare uygula → HS bas.
- Mage Polymorph + HS combo: lvl 8'den itibaren güvenli ölüm kaçışı.
- Warrior'ın Intercept (40 yard charge) + Disarm (Berserker Stance) HS güvenliği sağlar.

### 1.2 "Aggro Dump" trickleri
- **Vanish** (Rogue) — aggro tamamen siler; dungeon kaçışı için altın.
- **Feign Death** (Hunter) — 30% şansla başarısız olur (level 60'ta bile!), her zaman 2 deneme yap.
- **Invisibility** (Mage) — 10 sn fade + 10 sn invis; threat reset.
- **Shadowmeld** (Night Elf) — combat dışındaysan aggro reset; stealthed mob detect edemez. **HC night elf survivability avantajı.**
- **Dwarf Stoneform** — bleed/poison/disease remove + 10% armor; 8 sn invuln değil ama poison stack temizler.
- **Will of the Forsaken** — fear/charm/sleep break, 2 dakika CD; HC'de senin **2. canın**.

### 1.3 LoS (Line of Sight) Kullanımı
- Caster mob LoS kesilince hedef bırakır 2-3 saniye sonra. Köşede beklemek yerine **15+ yard arkaya kaç** ve LoS kes.
- Patrol görüşünden kaçınmak için "köşe çekme" (corner pull): tek mob'u köşeden vurarak ek-aggro engelle.
- Ranged class (Hunter, Mage, Lock, Priest) LoS abuse mob AI'a karşı en güçlü silah.

### 1.4 Run Speed manipülasyonu
- **Aspect of the Cheetah** (Hunter, lvl 16) — +30% speed, hit'te 4 sn daze. Patrol için harika; combat'tan önce kapat.
- **Travel Form** (Druid, lvl 30) — +40%, combat girilince düşer.
- **Spirit of the Wolf / Ghost Wolf** (Shaman, lvl 20) — +40%, combat'ta da açık kalabilir.
- **Crusader Aura** (Paladin, lvl 32) — +20% mounted, **dismounted'da +20% değil** — yanlış bilgi yaygın.
- **Engineering Goblin Rocket Boots** — 5 dakika CD, +70% 20 sn; ölüm kaçışı için #1 item.
- **Free Action Potion** — fear/root/snare immunity 30 sn; rooted-and-burned ölümünü engeller.

---

## 2. UI & Quality of Life

### 2.1 Mouse-over heal/buff
- Healer için **mouseover macro** zorunlu. Frame'i hedeflemeden cast:
  ```
  /cast [@mouseover,help,nodead][@player] Healing Light
  ```
- HC Priest/Druid/Pala için mouseover heal = 2x ölüm önleme.

### 2.2 Combat addonu kombinasyonu (HC zorunlu)
- **DeathLog / Hardcore Death Log** — sunucu çapında ölüm broadcast (TrueHorse).
- **HCT (Hardcore Tracker)** — kendi karakter cebrenin geçmişi.
- **Questie** — quest tracker + güvenli/tehlikeli quest filtreleme.
- **Threat-1 / TinyThreat** — threat-meter (60-öncesi raid yok ama dungeon için kritik).
- **OmniCC** — buton CD sayacı.
- **WeakAuras** — HP %25 alarm, racial CD alarmı.
- **Bagnon / Baganator** — bag ve bank consolidate.

> **HC** Full liste: [00-addonlar.md](00-addonlar.md)

### 2.3 Macro şablonları
- `/stopcasting /use 13 /use 14 /cast Blessing of Protection` — full panic save.
- `/cast !Auto Shot` (Hunter) — auto-shot kesilmesin.
- `/cast [stance:1] Battle Shout; [stance:2] Demoralizing Shout` (Warrior multi-stance).

---

## 3. Vendor, Reagent, Repair "Hidden Knowledge"

### 3.1 Limited stock vendor'lar
- **Yebb Neblegear** (Everlook, Winterspring) — Frost Oil reagent; HC kritik.
- **Logannas** (Felwood) — Free Action Potion reagent.
- **Andron Gant** (Stormwind) — Heavy Silken Thread, limited.
- Vendor refresh: ~5-10 dakika (Blizzard wantonsly random).

### 3.2 Yeniden basılan grenade limit
- **Solid Dynamite** — Engineering crafted, vendor satın alma yok. Stoğun olmalı.
- **Goblin Sapper Charge** (lvl 50, Engineering) — self-damage çok yüksek; emergency only.

### 3.3 Repair gold rule of thumb
- Lvl 30: ~50s repair
- Lvl 45: ~2g repair
- Lvl 60: ~5g full repair
- HC'de cebinde **her zaman repair'in 3x'i** olsun.

### 3.4 İnnkeeper Hot Tip
- **Hearthstone CD 60 dakika.** Yeni inn'e bind et = anında CD sıfır değil; HS CD korunur.
- **Astranaar Innkeeper Saelienne** kıyıda — HC Alliance #1 leveling hub.
- **Crossroads Innkeeper** — Horde #1 hub; ölüm yakın olabilir (PvP yok ama elite Centaur patrol).

---

## 4. Sosyal & Grup Dinamikleri

### 4.1 Grup bulma realm-spesifik
- **/who** komutu en güvenilir party finder.
- Anniversary HC realmlerinde channel: `/join HardcoreGroups` veya `/join LFG`.
- **Asla pug dungeon yapma** seninle exp/level dengesi olmayan biriyle. **Önerilen: dungeon başlamadan önce party'nin tüm class/level/spec'lerini gör.**

### 4.2 Trade-yerine workaround
- Mail/trade kapalı = item el değiştirmez. Çözüm: **same-account alt** mailing.
  - Para taşıma için alt karakterinden ana karakterine mail.
- **Group loot Master Loot** ile takım itemlerinde "needs first" sırası belirlenebilir.

### 4.3 Guild dinamikleri
- HC guildleri genelde **death broadcast disable** ister (chat spam azaltma).
- **Guild bank** birden çok kişinin item depolaması için kullanılır ama trade kapalı ⇒ guild bank withdraw da kapalı (bazı realm/server kombinasyonlarında). Teyit et.
- **Solo guild** (kendi guild'in) bank slot için: 200g + 5 imza gerekir (5 random oyuncudan); Anniversary HC realmlerinde rep grindi.

---

## 5. Lesser Known Sınıf-Spesifik Tüyolar

### 5.1 Warrior
- **Stance dance**: Berserker Stance'a geç → Berserker Rage (fear/sap immunity, 30 sn CD) → Battle Stance.
- **Bandage spam**: Defensive Stance'ta threat azalır; bandage kullanırken aggro dump.
- **Heroic Strike on next swing**: rage harcar, ek vuruşa katılır — düşman flee ederken bile.

### 5.2 Paladin
- **Blessing of Protection (BoP)**: kendine de basabilirsin; 10 sn physical immunity, melee mob için "panic button". **HC paladin'in ana hayat kurtarıcısı.**
- **Divine Shield + Bandage**: BS sırasında bandage kesilmez (5 sn lockout var ama yine de).
- **Lay on Hands**: 60 dakika CD; full HP heal — **sadece ölüm anı için**.

### 5.3 Hunter
- **Feign Death güvenirsizliği** — %30 fail oranı. Backup planın olmalı.
- **Pet sacrifice**: Mend Pet ile pet HP'sini doldur, pet tank yap, sen kaç.
- **Beast Lore** ile mob HP'sini gör (oyun içinden).
- **Disengage** (Survival, lvl 20) — geri jump, threat azaltır.

### 5.4 Rogue
- **Vanish + Stealth + Sap** zinciri ile herhangi bir grubu skip et.
- **Blind** (lvl 56) — 10 sn disorient. Major escape.
- **Sprint + Vanish + Sprint** ile uzun mesafe kaçış.

### 5.5 Mage
- **Frost Nova → Blink** (5 yard arkaya teleport) → Frost Nova → Polymorph zinciri.
- **Cold Snap** (Frost) — tüm Frost CD'leri reset; Frost Nova spam.
- **Mana Shield** + **Evocation** dependable survival.
- **Polymorph farm**: tüm packı poly + sheep, tek tek vur.

### 5.6 Warlock
- **Soulstone** kendine bas — ölünce 30 sn içinde rez. **HC'de "ikinci can"**, ama uyarı: rez sonrası mob hala saldırır.
- **Healthstone** her zaman elinde; cooldown party-wide cooldown.
- **Fear kiting**: Curse of Exhaustion + Fear, mob kaçarken DoT spam.
- **Drain Life** + **Siphon Life** + **Dark Pact** — full life tap setup.

### 5.7 Druid
- **Travel Form'da combat girilince düşer** ama yine düşmadan önce 5 yard rush yapabilirsin.
- **Innervate** kendine kullan = mana refill; HC kritik.
- **Barkskin** + **Frenzied Regeneration** (Bear) tank için temel.
- **Cat Form Dash** (40% speed) — combat dışı kaçış.

### 5.8 Priest
- **Power Word: Shield** + **Renew** + **Bandage**: ranged kiting setup.
- **Mind Soothe** (lvl 8) — mob aggro radius azaltır. Patrol skip için altın.
- **Shadowform** (lvl 40) — damage 15% boost ama healing engelli; HC için Shadow'a girince geri çıkış zor.
- **Fade** (lvl 8) — threat dump, 10 sn.

### 5.9 Shaman
- **Earthbind Totem** (lvl 6) — area snare. Multi-mob için patrol.
- **Frost Shock** — single target snare.
- **Astral Recall** (lvl 30) — Hearthstone gibi ama 15 dakika CD, ayrı CD; **HC ikinci HS**.
- **Reincarnation** (lvl 30) — 60 dakika CD self-rez. **HC Shaman'ın altın kartı.** Ölümden 1 saatte 1 kez dönebilir.

> **HC** Reincarnation **karakter ölümünü iptal etmez!** Karakter teknik olarak ölür ama hala oynanabilir. Sadece Blizzard HC realm'de bu OK (rez kuralı içinde). Community HC (pre-Blizzard) rule'larında Reincarnation yasaktı.

---

## 6. Profession & Gold Tüyoları

### 6.1 Profession Pairing (HC için best combos)
- **Engineering + Mining** — parachute cloak, dynamite, jumper cables, Goblin Glider.
- **Alchemy + Herbalism** — own potions; Free Action Potion HC için altın.
- **Tailoring + Enchanting** — own bag, own enchants; Spirit/Stamina enchants survival.
- **Leatherworking + Skinning** — Devilsaur Set (45-58), Volcanic Set (50-60).

### 6.2 Bağımsız Gold Sources (AH yok, AH bağımlı satışlar imkansız)
- **Vendor reagents** (Dust, Symbol of Divinity etc.) limited stock → vendor'dan al, yine vendor'a sat değil; sadece kendi craft için.
- **Trash mob loot** vendor sell: cloth (Silk, Mageweave, Runecloth), random weapons.
- **Dungeon BoP gear** sat: drop edilen yeşil/mavi itemlerden ihtiyaç olmayan vendor'a sat.

### 6.3 Cooking + Fishing combo
- **Smoked Sagefish** (Sagefish + Mild Spices) — Mana regen food, lvl 10+.
- **Stormchops** / **Spiced Wolf Meat** — Stamina food.
- **Mighty Rage Potion** crafting (Alchemy) için herb farm.

---

## 7. Hidden Quest Reward & Item Tüyoları

### 7.1 BoA / Special items
- **Bind on Pickup** itemler trade edilemez; kendi karakterin için yapılmış.
- **Whitemane Inquisitor's Cloak** (SM Cathedral, "Mythic" ranged drop) — DPS cloak.
- **Tome of First Aid: Expert** (Hillsbrad/Arathi) — First Aid 225+ unlock; her HC karakter almalı.

### 7.2 Mount tüyoları
- Lvl 40 mount: 80g (talent+riding skill 100g toplam; rep discount ile 60g'ye iner).
- **HC** Rep discount (Honored: 10%, Revered: 20%) — Stormwind/Ironforge/Darnassus/Exodar reputation grindi yap.
- Lvl 60 epic mount: 1000g; HC'de epic mount ulaşılabilir ama %95 oyuncu basic mount ile kalır.

### 7.3 Quest text okuma kuralı
- Quest verici "be careful" / "dangerous" / "elite group" / "group only" yazarsa **3+ kişi yoksa pas geç**.
- Quest hata mesajı: "Requires a party" → grup quest, **solo asla**.

---

## 8. PvP & Mak'gora Etik

### 8.1 Mak'gora kabul edilirse
- Tüm consumables, buff stacking, gear swap kabul.
- **Disengage + run** stratejisi var (genelde Hunter/Mage); kabul edip kaçarsan teknik olarak meşru.
- **Önce duel'i kabul etmeden inspect et** — gear/level dengesizliği görürsen kabul etme.

### 8.2 Faction NPC aggro
- Yanlışlıkla Crossroads/Goldshire guard pull etmek faction war flag açar; **HC** realm'de PvP normalde kapalı ama bu durumda enemy faction tarafından öldürülebilirsin.
- **Çözüm:** /sit + ranged kaçış; guardlar 60 yard sonra de-aggro.

---

## 9. Risk Yönetimi (Genel HC Felsefesi)

1. **"Hızlı vs güvenli" — her zaman güvenli.** 5 dakika ekstra > 50 saat geri.
2. **Tehlikeli quest skip** — XP eksik gibi görünür ama 60'a kadar her quest gereksizdir; total 60'a giden quest sayısı ~600+, sen 350 quest ile bitebilirsin.
3. **Sokağı tanı**: bilmediğin zone'a girmeden önce Wowhead/Questie açık.
4. **Combat öncesi: HP/Mana >85%, CD'ler hazır, escape route belli.**
5. **Multi-mob > 2 = full run.** Mage hariç (Frost Nova kombo).
6. **Tanımadığın oyuncuya güvenme** — dungeon DC, pull-and-leave standart.

### 9.1 Streamer / OnlyFangs gözlemleri
- En tecrübeli streamerlar bile ortalama her 2-3 karakter 60'tan önce ölüyor.
- **Sodapoppin** stratejisi: under-leveled quest, asla zone'un üst seviyesinde grind.
- **Asmongold** stratejisi: paladin/druid gibi tankı yüksek class seç, dungeon spam yerine quest yap.
- **Bobsmade** stratejisi: druid + first aid + alchemy üçlüsü, solo dungeon kaçışı.

---

## 10. "Trap" Item ve Quest'ler (DIKKAT)

| Item / Quest | Tehlike |
|---|---|
| **Cursed Cutlass** (drop, STV) | Equip edilince debuff stack; HC ölüm |
| **Carrot on a Stick** (lvl 40+ trinket) | Yararsız ama gear slot işgal |
| **Cap of the Free Thinker** (1.15 anniversary) | XP buff trinket; combat'a girince kayıp |
| **The Princess Trapped** (Maraudon questline) | Yanlış instance girince lockout harcanır |
| **Dorgar / Quest item drop** | %1 droplar günler boyu farm; HC zaman riski |
| **Power Word: Fortitude rank max** (Priest) | Auto-buff macro yanlış cast = mob pull |

---

## Kaynaklar
- r/HardcoreWoW community wiki (FAQ, hidden tips, dangerous content)
- hardcore.wiki.gg (community-edited)
- Hardcore Discord (OG HC + Bloodsail Buccaneers + OnlyFangs)
- YouTube: Bobsmade, Defcamp & Melderon TV, MadSeasonShow (HC retrospectives)
- Streamer veriler: Sodapoppin, Asmongold, Esfand, Soulsobreezy (HC raid)
- Wowhead comment ölüm uyarıları (Classic Era)
- Hardcore Death Log addon community data (TrueHorse)
- Anniversary realm community Discord (2024-2026)
