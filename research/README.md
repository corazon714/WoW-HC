# WoW Classic Hardcore — Araştırma İndeksi

**Son Güncelleme:** 2026-06-18
**Versiyon Kapsamı:** Classic Era 1.15.x + Anniversary HC (Classic Fresh) Realmleri
**Birincil Resmi Kaynak:** Wowhead Classic Hardcore Hub — https://www.wowhead.com/classic/guides/hardcore

Bu klasör, WoW Classic Hardcore üzerine derinlemesine araştırma dosyalarını içerir. HTML guide üretimi için temel kaynak olarak kullanılır (bkz. ana `claude.md`).

> **🚨 KRİTİK — İki Farklı HC Realm Tipi**
> 
> Araştırmalar **iki ayrı HC realm sistemini** kapsar:
> - **Original HC** (Ağu 2023 — Bloodsail Buccaneers NA, Doomhowl EU): Cheat death mekanikleri (Paladin Bubble Hearth, Warlock Soulstone, Shaman Reincarnation) **AÇIK**.
> - **Classic Fresh HC / Anniversary HC** (Kas 2024+ — Defias Pillager NA, Skull Rock EU, Lava Lash, Soulseeker): Tüm cheat death mekanikleri **DEVRE DIŞI**. Soul of Iron buff, lvl 60+düşük level dungeon mix yasağı, Survivor titles.
> 
> Detaylar: [00-genel-kurallar-mekanikler.md](00-genel-kurallar-mekanikler.md) (Bölüm 0 + 8).

---

## Foundation Dosyaları (Her Race/Class HTML Guide'ı İçin Zorunlu)

| Dosya | İçerik |
|---|---|
| [00-genel-kurallar-mekanikler.md](00-genel-kurallar-mekanikler.md) | Blizzard official HC rules, Original vs Classic Fresh realm farkı, death, lockout, trade/mail/AH, dungeon kuralları, ölüm istatistikleri |
| [00-tehlike-haritalari.md](00-tehlike-haritalari.md) | Tüm zonelar için danger map, Wowhead resmi "Dangerous Quests" listesi, elite patrol listesi, çevresel tuzaklar |
| [00-community-good-to-knows.md](00-community-good-to-knows.md) | Wowhead resmi Leash/Thrash/Daze mekanikleri, community 100+ tüyo, kamera macro, escape mechanics |
| [00-addonlar.md](00-addonlar.md) | Essential + Good to Have + Class-Specific addon listesi, konfigürasyon, WeakAuras paketleri |
| [00-professions-ekonomi.md](00-professions-ekonomi.md) | Wowhead resmi profession önerileri (Eng+Mining / Alch+Herb), class × profession matrisi, gold yönetimi |
| [00-dungeon-kurallari.md](00-dungeon-kurallari.md) | 1-60 arası tüm dungeon, Classic Fresh lvl 60-mix yasağı, cheat death disabled, lockout, must-have gear |

---

## Class Araştırmaları (`classes/`)

Wowhead HC Tier List (Calamityhc, son güncelleme 2024-11-20, "Fresh HC + 20th Anniversary için de geçerli"):
- **S Tier:** Mage, Paladin, Rogue
- **A Tier:** Hunter, Warlock, Druid
- **B Tier:** Priest, Shaman
- **C Tier:** Warrior

| Dosya | Wowhead Tier | HC Difficulty | Notable HC Strength |
|---|---|---|---|
| [warrior.md](classes/warrior.md) | C | **YÜKSEK** (1-30), ORTA (30-60) | Mortal Strike (40+), Sul'thraze BiS, plate armor |
| [paladin.md](classes/paladin.md) | **S** | DÜŞÜK | BoP + Lay on Hands + Blessings; **Bubble Hearth Classic Fresh'te KAPALI** |
| [hunter.md](classes/hunter.md) | A | DÜŞÜK | Pet tank, Feign Death, Aspect of Cheetah, en güvenli ranged |
| [rogue.md](classes/rogue.md) | **S** | ORTA | Stealth + Vanish + Sprint = patrol skip master |
| [priest.md](classes/priest.md) | B | ORTA | PWS + Renew + Vampiric Embrace sustain; Dwarf Priest Fear Ward = endgame BiS |
| [mage.md](classes/mage.md) | **S** | DÜŞÜK-ORTA | Frost Nova + Blink + Ice Block, kontrol master, food/water self-conjure |
| [warlock.md](classes/warlock.md) | A | DÜŞÜK | Pet tank, DoT + Drain Life sustain; **Soulstone Classic Fresh'te KAPALI** |
| [druid.md](classes/druid.md) | A | DÜŞÜK-ORTA | Travel Form (mount yok), Bear/Cat versatility, self-heal |
| [shaman.md](classes/shaman.md) | B | ORTA | Ghost Wolf, totem utility (grupta güçlü); **Reincarnation Classic Fresh'te KAPALI** |

---

## Race Araştırmaları (`races/`)

### Alliance
| Dosya | HC Tier | Notable Racial |
|---|---|---|
| [human-racials.md](races/human-racials.md) | B | Diplomacy (rep grindi), Sword/Mace Spec |
| [dwarf-racials.md](races/dwarf-racials.md) | A | Stoneform (poison/bleed/disease wipe), Gun Spec, **Dwarf Priest Fear Ward** |
| [night-elf-racials.md](races/night-elf-racials.md) | **S** (Druid/Rogue) | Shadowmeld (out-of-combat stealth) |
| [gnome-racials.md](races/gnome-racials.md) | A (caster) | Escape Artist, +%5 Int, Engineering Spec |

### Horde
| Dosya | HC Tier | Notable Racial |
|---|---|---|
| [orc-racials.md](races/orc-racials.md) | **S** (Warrior/Shaman) | Hardiness +%25 stun resist, Blood Fury, Axe Spec |
| [undead-racials.md](races/undead-racials.md) | **S** (Lock/Priest) | **Will of the Forsaken** (anti-fear, HC #1 emergency) |
| [tauren-racials.md](races/tauren-racials.md) | **S** (Druid/Warrior) | **War Stomp** (AoE stun, in form too), +%5 HP |
| [troll-racials.md](races/troll-racials.md) | **S** (Hunter) | Bow Spec, Regen (combat'ta bile), Berserking |

---

## Patch & Versiyon (`patches/`)

| Dosya | İçerik |
|---|---|
| [1.14-1.15-degisiklikler.md](patches/1.14-1.15-degisiklikler.md) | HC launch (1.14.4, Ağu 2023) → Anniversary launch (1.15.1, Kas 2024) → 1.15.6 (Yaz 2026) tüm HC-spesifik patch değişiklikleri |

---

## HTML Guide Üretim Akışı (Hatırlatma)

Bir race+class HTML guide istendiğinde:

1. **Foundation dosyaları** (yukarıdaki 6 ana dosya) okunur.
2. **İlgili class dosyası** (örn. `classes/druid.md`) okunur.
3. **İlgili race dosyası** (örn. `races/night-elf-racials.md`) okunur.
4. **Patch dosyası** versiyon farkı kontrolü için referans alınır.
5. HTML guide `/guides/[race]-[class]/index.html` olarak yazılır.
6. Race racial'ları **build + checklist + PvP** bölümlerine **kullanım örnekleriyle** entegre edilir.

---

## Eksik / Genişletilebilir Konular

İhtiyaç doğdukça araştırma genişletilebilir:
- **Dungeon-spesifik tek dosyalar** (`dungeons/scarlet-monastery.md`, `dungeons/blackrock-depths.md` gibi): mevcut bilgi `00-dungeon-kurallari.md`'de konsolide; ihtiyaç olursa per-dungeon detaylı dosya.
- **Raid rehberleri** (MC, BWL, AQ40, Naxx) — Anniversary HC raid content.
- **Specific build deep-dive** (örn. Mortal Strike vs Fury vs Prot deep math).
- **PvP/Mak'gora arena meta** — community Mak'gora tournament strategies.

---

## Ana Kaynaklar (Tüm Dosyalar Genelinde)

### Wowhead Resmi Classic Hardcore Hub
- **Hub:** https://www.wowhead.com/classic/guides/hardcore
- **Overview (Cheat Death mekanikleri, realm tipleri):** https://www.wowhead.com/classic/guide/hardcore-wow-overview
- **Tips & Tricks (Leash/Thrash/Daze, dangerous quests):** https://www.wowhead.com/classic/guide/tips-and-tricks-hardcore
- **Tier List (Calamityhc, 2024-11):** https://www.wowhead.com/classic/guide/classes-hardcore-tier-list
- **Class HC Leveling Guides (9 class):** https://www.wowhead.com/classic/guide/classes/[class-name]/hardcore-leveling-tips

### Diğer Birincil Kaynaklar
- **Blizzard official HC FAQ** (forum sticky, Aug 2023) + 1.15 patch notes
- **hardcore.wiki.gg** (community-edited)
- **Hardcore Death Log addon** (TrueHorse) — ölüm verisi heatmap
- **r/HardcoreWoW** + **r/classicwow** community discussion
- **Hardcore Discord** (OG HC + Bloodsail Buccaneers + OnlyFangs)
- **YouTube content creators**: Bobsmade, Defcamp & Melderon TV, DesMephisto, Snutz, Kargoz, MadSeasonShow, Sodapoppin, Asmongold, Esfand, Soulsobreezy
- **Class-specific Discord** sunucuları (Warrior/Paladin/Hunter/etc. Classic discord communities)
