The sounds have been properly refreshed


Regarding the build:
* Remove all confusing and bloating AudioPackage*.mk but AllAudio.mk.
* Modify generate-all-audio.sh and AllAudio.mk to copy sounds into
    build in a more intuitive PRODUCT_COPY_FILES step.

Regarding the sounds:
* Reorganize all sounds.
* Remove only the ancient and dead ones.
* Use KitKat ui sounds.
* Relocate sounds in /newwavelabs into their proper category
    according to AudioPackage*.mk.
* Remove smaller ones for the duplicates
    as they are expected to have relatively poor quality.



声音已经过大换血


关于编译:
* 删除所有复杂且累赘的AudioPackage*.mk仅保留AllAudio.mk.
* 修改generate-all-audio.sh和AllAudio.mk
    将声音以一个更直观的PRODUCT_COPY_FILES步骤复制进包中.

关于声音:
* 重新整理所有声音.
* 删除过时严重的和不再使用的声音.
* 使用KitKat的ui声音.
* 将newwavelabs目录中的根据AudioPackage*.mk
    中定义的类别分放进各自的目录.
* 删除尺寸较小的重复声音
    因为他们相对音质差一些.
