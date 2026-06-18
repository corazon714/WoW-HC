# WoW Classic Hardcore — Addon Rehberi

**Versiyon:** Classic Era 1.15.x / Anniversary HC (Classic Fresh)
**Son Güncelleme:** 2026-06-18
**Kapsam:** HC'de **Essential**, **Good to Have**, **Class-Specific** addonlar ve önerilen konfigürasyonlar.

## Özet
HC'de addon seçimi sıradan Classic'tekinden farklıdır: ölüm broadcast, threat takibi, panic alert ve quest güvenlik filtresi temel ihtiyaçlardır. Bu liste 2026 itibariyle aktif maintained ve Anniversary HC realmlerinde test edilmiştir.

---

## 1. Essential (Olmazsa Olmaz)

| Addon | Geliştirici | İşlev | Neden HC |
|---|---|---|---|
| **Hardcore** | DesMephisto / Eternal-Dev | Resmi HC addon (community), level/death/realm tracker, "Verification System" | Karakter geçmişi proof; pre-Blizzard HC için zorunluydu, hala faydalı |
| **Hardcore Death Log** | TrueHorse | Sunucu çapı ölüm broadcast, kim/nerede/nasıl | Mob/zone tehlike farkındalığı |
| **Questie** | Questie Team | Quest tracker, world map quest objektifleri | Yanlış zone/quest = ölüm; Questie filtreler |
| **Atlas / AtlasLoot Classic** | Atlas Team | Dungeon map + loot table | Dungeon öncesi planlama (lockout 1) |
| **Threat Classic 2 / TinyThreat** | Various | Threat meter (Omen yerine) | Tank/DPS/healer aggro yönetimi |
| **OmniCC** | Tuller | Tüm cooldown'lara sayaç ekler | Panic CD'leri (PoM, BoP, FAP) takibi |
| **WeakAuras 2** | Stanzilla / Mods | Custom HP/CD/buff alert | "HP <%30 alarm", racial CD ready |
| **Bagnon / Baganator** | Tuller / Plusmouse | Tüm bag/bank tek pencere | Inventory yönetimi |
| **Details! Damage Meter (Classic)** | Tercio | Damage/healing meter | Group composition kontrol |
| **Leatrix Plus (Classic)** | Leatrix | Auto-repair, auto-sell, vendor tools, QoL | Repair gold otomasyon |

> **HC** Yüklemen gereken minimum 5: Hardcore, Hardcore Death Log, Questie, Threat Classic 2, WeakAuras 2.

---

## 2. Good to Have (Önerilir)

| Addon | İşlev | Notlar |
|---|---|---|
| **Pawn** | Item upgrade scorer | Loot decision hızlandırır |
| **Plater Nameplates** | Custom nameplate (cast bar, threat color) | Cast interrupt mantığı için kritik (interrupt class'lar) |
| **PallyPower** | Paladin blessing yöneticisi | Class composition'a göre blessing dağılımı |
| **Healbot Continued / VuhDo** | Click-cast heal frame | Healer (Priest/Druid/Pala/Shaman) için altın |
| **Decursive** | Tek tıkla debuff temizle | Healer + utility |
| **GatherMate2 + GatherMate2_Data** | Herb/mining/treasure node harita | Gathering profession için |
| **TomTom / Cartographer Waypoints** | Coordinate waypoint | Quest objektif yönlendirme |
| **Skada** | Alternatif damage meter (Details! yerine) | Lighter |
| **MoveAnything** | UI frame'leri özgürce taşı | UI rearrangement |
| **Auctionator (Classic)** | AH replacer (HC'de AH yok ama Era realmleri için saklı) | Sadece Era için |
| **MaxDps Classic** | Rotation suggester (next-spell hint) | DPS class learning |
| **WIM (WoW Instant Messenger)** | Whisper window manager | Sosyal yönetim |

---

## 3. Class-Specific Addonlar

### Warrior
- **ClassicCastbars** — boss cast bar timing.
- **MyDots** (rage check) — Sunder Armor stack izleme.
- **RageX** — rage bar UI.
- **Battleground Targets** — PvP için (Anniversary HC raid).

### Paladin
- **Decursive** (debuff cleanse) — Cleanse spam.
- **PallyPower** — blessing sync.
- **Holy Power Pala WA** — Holy Light vs Flash heal decision (custom WA).

### Hunter
- **BadBoy / Hunter Helper** — pet management, focus dump.
- **TrapHelper** — trap CD/macro.
- **Quartz Cast Bar** — Auto-shot timer.

### Rogue
- **Energy Watch / EnergyTick** — energy regen tick visualizer.
- **Combo Points Redux** — combo point UI.
- **Sap Helper** — sap macro & dungeon CC tracker.

### Priest
- **HealBot Continued** veya **VuhDo** — click-cast heal.
- **NeedToKnow** — DoT/HoT tracker.
- **PhBuffs** — buff debuff tracker.

### Mage
- **MageHelper** — Polymorph CC tracker.
- **Conjuror** — food/water reagent counter.
- **PolyMonitor** — multi-poly assist (5-man dungeon).

### Warlock
- **DotTimer / Necrosis** — DoT/curse tracker.
- **Soulstone Reminder** — Soulstone CD alarm.
- **Healthstone Helper** — party HS tracking.

### Druid
- **NugComboBar** — combo points + form tracker.
- **DruidBar** — manapool track in non-mana forms.
- **CatHelper** — DPS rotation hint.

### Shaman
- **TotemTimers** — totem CD ve drop UI.
- **Reincarnation Tracker** — Reincarnation CD (HC ikinci can).
- **Shockwatch** — Earth/Frost Shock CD.

---

## 4. UI Replacement Suites (Comprehensive)

- **ElvUI Classic** — full UI replacement, nameplates+actionbar+chat+raid frames bir arada.
- **NDui Classic** — Çinli toplulukta popüler; lightweight ElvUI alternatifi.
- **Tukui Classic** — Minimalist; performance odaklı.
- **SUI / SyncUI** — community config preset.

> **Not:** Suite addonları diğer addonların çoğunu içerir veya çakışır. Önce suite, sonra eksikleri ekle.

---

## 5. Konfigürasyon Önerileri

### 5.1 WeakAuras (HC için temel set)
Önerilen Wago.io paketleri:
- **"HC Survival Pack"** (search: "hardcore survival") — HP %30 alert, healing potion CD, racial CD.
- **"Hardcore Mode WA"** — yaklaşan elite mob warning, low-HP party alert.
- **"Class CC Tracker"** — Mage Poly, Warrior Disarm, Hunter Trap durumu.

### 5.2 Plater Nameplate Profile
- **"HC Plater Profile"** (Wago) — kırmızı renk = elite mob; sarı = patrol; mavi = friendly NPC.
- Cast bar mutlaka açık; interrupt-able casts'lar **vurgulanmış**.

### 5.3 Questie Filters
- Düşman seviyesinin >3 üzerindeki questleri filtrele (otomatik gri).
- "Show DungeonQuests" — açık tut ama gözle seç (HC'de dungeon questleri yapma kararı zor).

---

## 6. Yasak / Tehlikeli Addon Davranışları

Blizzard, aşağıdaki addon davranışlarını HC realm'de **suspend edilebilir** olarak işaretler:
- **Auto-decline duel** — Mak'gora /makgora reddetmek meşru, ama otomatize edilirse şüpheli.
- **Pixel walker / wall-walk macro** — exploit.
- **Multi-character broadcast** — multibox software entegresi.

**Güvenli kural:** Addon sadece UI ve information assistance yapsın; oyun kararı vermesin.

---

## 7. Addon Yönetimi Tüyoları

- **CurseForge** veya **WoWUp.cf** uygulamaları ile addon yönet (manual ZIP yüklemekten kaçın).
- Patch sonrası %80 addon bir hafta out-of-date olabilir; **DropDownList** / library updateleri gerekir (Ace3, LibStub).
- **Adsız** addonları yükleme; Trojan riski.
- Karakter başına farklı profil tut (Healer vs DPS UI farkı).

---

## Kaynaklar
- CurseForge HC tag (en aktif maintained listesi)
- Wago.io WeakAuras hardcore search
- r/HardcoreWoW addon megathread (yıllık güncelleme)
- hardcore.wiki.gg addon recommendations
- WoWUp HC profile sharing
