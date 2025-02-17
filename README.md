# Mi439 Dynamic Partition Manager 🔧

**A TWRP flashable tool for Mi439 Devices to resize the system partition while preserving vendor space**

---

## 📌 Features
- **Dynamic System Resizing** (6GB-15GB via filename)
- 🛡️ **Safety First** - Maintains original partition alignment
- 🔄 **Restore Support** - Return to stock partition table
- 📱 **TWRP Compatible** - Works with custom recoveries
- 💾 **Auto-Formatting** - Creates fresh EXT4 filesystems

---

## 📥 Downloads
[![Latest Release](https://img.shields.io/badge/download-latest-blue)](https://github.com/nimafanniasl/Mi439-RePartitioner/releases/latest)
- `Mi439_repartition.zip` - Main tool
- `Mi439_restore_original_partition_table.zip` - Stock layout restore

---

## ⚡ Quick Start

### Prerequisites
- Unlocked bootloader
- Custom recovery (TWRP/OFOX)
- **Backup important data!**

### Installation
1. **Flash Repartitioner**:
   ```bash
   # Default 6GB system
   Install → Mi439_repartition.zip

   # Custom size (e.g., 10GB)
   Rename to: Mi439_repartition_10GB.zip → Flash
   ```

2. **Restore Original Layout**:
   ```bash
   Install → Mi439_restore_partitions.zip
   ```

---

## ⚠️ Critical Warnings
- **‼️ BREAKS DYNAMIC PARTITION SUPPORT**
  - After flashing repartition ZIP:
    - **Can't install** dynamic ROMs
    - **Must flash restore ZIP** first

- **🔁 Repartitioning Rules**:
  - **Always restore** before changing sizes again


## 💬 Support
**Found a bug?** Open an [issue](https://github.com/nimafanniasl/Mi439-RePartitioner/issues)

---

## Credits
- Developed by **[Nima Fanniasl](https://smartnima.com)**
- Telegram: [@NimaFanniasl](https://t.me/NimaFanniasl)
