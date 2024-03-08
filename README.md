# obfuscator-list
* [AckerRun](https://github.com/YumeGod/AckerunObfOpenSource) - FOSS. Lightweight/Heavy obfuscator depanding on your config. Has some interesting features that not every other obfuscator has. Looks like XenonGuard skid but I can't confirm that.
* [Allatori](http://www.allatori.com/) - Commericial. Somewhat popular choice in industry.
* [Ambien](https://github.com/iiiiiiiris/Ambien) - FOSS. Obfuscator that is not getting actively developed anymore. Has some cool packaging features mainly targeting Recaf 2x with a great succeed since their RedHerring feature adds a fake jar before the real one. Most RE tools don't read backwards like the JVM, so they will read the fake jar. Also has a decent Crasher transformer that confuses various decompilers & other reverse engineering tools. Still contain some bugs/issue to this day.
* [Avaj](https://github.com/cg-dot/avaj) - FOSS. Has a nice way of generating decryption subroutines on string constants. Also has some CFG flattening which is always nice to see.
* [Binscure](http://www.bisguard.com/) - Commercial. Binscure was a commercial Java obfuscator that had a running spat with Recaf. Its primary advertised features were its crasher and zipping abilities and intense flow/indy obfuscation. However as with most cat-and-mouse games, one side would give up. Since we're using past tense here, its Binscure if you haven't caught on. The ASM/RE tool crashers are now fully patched in Recaf with current versions. The flow and indy obfuscation still is fair for the current market. Can be deobfuscated using [Narumii](https://github.com/narumii/Deobfuscator)/[JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator)
* [BisGuard](http://www.bisguard.com/) - Commercial. It's a Java packer for the insane asking price of $1200. All it does is wrap your jar with a simple cipher. There is no additional protection. Relies entirely on class encryption (last time I checked, at least) so protection has quite a bit of room for improvement. BisGuard has no configuration because it only has the packing feature. Seems to be really buggy for the asking price of $1200. Breaks MANIFEST files.
* [Black](https://github.com/CodingGay/BlackObfuscator) - FOSS. Black Obfuscator is an obfuscator for Android APK DexFile, it can help developer to protect source code by control flow flattening, and make it difficult to analyze the actual program control flow.
* [Bozar](https://github.com/vimasig/Bozar) - Points for FOSS. Has some cheap tricks along with GUI that I have seen being used in the Minecraft community. Can be deobfuscated using [Narumii](https://github.com/narumii/Deobfuscator).
* [BranchLock](https://branchlock.net/) - Commercial. An online, web-based obfuscator primarily known for its AntiDebugging features. It advertises itself as 'modern, lightweight, but powerful,' which is now untrue, considering that it can't compete with modern obfuscators anymore. It appears somewhat in the Minecraft community. However, it no longer receives updates.
* [Caesium](https://github.com/sim0n/Caesium) - FOSS. Has a transformer that implements a well-known HTML injection into any Java reverse-engineering tool that parses HTML tags. Shows alot in Minecraft community. Can be deobfuscated using [Narumii](https://github.com/narumii/Deobfuscator). 
* [CheatBreaker](https://github.com/CheatBreaker/Obf) - FOSS. Decent obfuscation that looks similar to Caesiums (Prob. Skidded). Obfuscation is overall decent. Shows in Minecraft community. Can be deobfuscated using [JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator)
* [ClassGuard](https://zenofx.com/classguard/) - Commercial. Relies mostly on class encryption with hardcoded AES keys in native libs. Pretty easy IDA/Binary Ninja/Ghidra exercise if you want to flex on your blog on something. Can be deobfuscated using [JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator).
* [CodeEncryptor+](https://github.com/4ra1n/code-encryptor-plus) - FOSS. It's 3 days old while im typing this. This project uses JNI to encrypt bytecode and JVMTI to decrypt bytecode in order to protect code. It provides two DLL files: one for encryption and one for decryption. During actual execution, only the decryption DLL file is used. It supports custom keys and package names. The encrypted Class files becomes malformed and cannot be parsed. Apart from retaining the Magic part at the beginning, the rest becomes unrecognizable bytes.
* [Colonial](https://github.com/ColonialBuilders/ColonialObfuscator) - FOSS. Rename of [Simple Obfuscator](https://gitlab.com/nickfreeman/SimpleObfuscator).
* [DashO](https://www.preemptive.com/products/dasho/overview) - Commercial. Shows up a bit in industry and has some interesting ideas (albeit probably outdated) in flow obfuscation. Can be deobfuscated using [JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator).
* [DexGuard](https://www.guardsquare.com/dexguard) - Commercial. Mainly used for obfuscating Android apps. Never saw any samples. Can be deobfuscated using [JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator).
* [Eskid](https://github.com/PlutoSolutions/EskidRewrite) - Commercial. Decent obfuscator based on [HsGuard](https://github.com/3000IQPlay/HsGuard-Obfuscator)/[Scuti](https://github.com/netindev/scuti/tree/master). Shows alot in Minecraft community. Could be possibly deobfuscated using [Ackeruns](https://github.com/AckerRun1337) Eskid deobfuscator trasnformer. Got cracked by [PlutoSolution](https://github.com/PlutoSolutions).
* [GOTO](https://github.com/Dimples1337/goto-java-obfuscator) / [GOTO](https://github.com/KgDW/GOTOObfuscator) - FOSS. A obfuscator made by chinese ppl written in Kotlin. Has interesting features but they are kinda broken.
* [Grunt](https://github.com/SpartanB312/Grunt) - Obfuscator written in Kotlin. Can be used as main obfuscator all tho there are missing some features such as Crasher or Flow obfuscation. Overall has very good features that are compatible with each other. Mainly known in Minecraft Comunity for it's mixin support renamer, native candidates and compatibilty with obfuscating Forge mods/Plugins. Contains some features that can be found in paid obfuscators.
* [HsGuard](https://github.com/3000IQPlay/HsGuard-Obfuscator) - FOSS. Obfuscator developed by Chinese ppl. Bad skid of Scuti with minimal additions. Can be deobfuscated using [Narumii](https://github.com/narumii/Deobfuscator).
* [J2CC](https://java2cc.github.io/) - Commercial. A new transpiler on the market going for $100 per personal license. I don't really have much to say about it right now since I just discovered it today but here is a [sample](https://cdn.discordapp.com/attachments/1210858230335541289/1210863487434227743/TSMrgXL.jar?ex=65ec1b80&is=65d9a680&hm=7466802570f7f137dfdbe0d61abe13a4cdea7338f725f79bda8256fee906d632&) provided by the developer him self.
* [JNIC](https://jnic.dev) - Commercial. One of not so many Java Native Interface Compilers that offers String Encryption, Control Flow with Flattening and their famous Native compiler. This obfuscator is mainly used for the Native compiling and does a really good job doing so. You can often see JNIC in Intent/1.8 cheat clients. Be aware that the Native obfuscation could cause lag or slow down the processes made in the application. If you would decide to use JNIC for obfuscation then make sure to not use it on it's own and instead use something with it.
* [JBCO](http://www.sable.mcgill.ca/JBCO/) - FOSS. Some interesting flow obfuscation techniques that still work in modern Java. Based on the [Soot](https://github.com/soot-oss/soot) library which is also something worthwhile checking out.
* [JObf/Sb27](https://github.com/superblaubeere27/obfuscator) - FOSS. Pretty outdated. Due to the generic name is more commonly referred to by the author's name superblaubeere27 / sb27. Has some basic features along with a GUI. Still shows allot in the Minecraft Community (Mainly in Japanese/Chinese Anarchy Clients). Can be easily deobfuscated with no effort using [Narumii](https://github.com/narumii/Deobfuscator)/[JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator).
* [JObfuscator](https://www.pelock.com/products/jobfuscator) - Commericial. Most of the obfuscated code are just int/double arrays with some light flow obfuscsaction (Based off sample). Uses polymorphic algorithm for strings encryption. Has only few features. Last update was made on 09.08.2022 which is a version 1.10.
* [Mosey](https://github.com/Hippo/Mosey) - FOSS. Outdated obfuscator mainly coded in Scala. Overall is no recommended for use since the obfuscation is very light and is easy to deobfuscate. Mainly used for 2+. layer obfuscation. Can be deobfuscated using [Narumii](https://github.com/narumii/Deobfuscator).
* [MyJ2C](https://github.com/MyJ2c/Open-MyJ2c) - FOSS. Obfuscator made by chinese ppl that managed to skid some of Allatoris parts such as String Enc. and some other things into their project. Overall only recommend using it when u have nothing else to use. Can be partically deonfuscated using Allatori deobfuscator. Has a interesting feature called "Confusing CallSites".
* [NeonObf](https://github.com/MoofMonkey/NeonObf) - FOSS. Made up of the easier to defeat obfuscation techniques.  NeonObf is also the name inspiration for Radon.
* [Obzcure](https://obzcu.re/) - [Discord](https://discordapp.com/invite/fUCPxq8) (Dead) - Commericial. Web-based obfuscation service with some inspiration taken from Radon and [SkidSuite2](https://github.com/GenericException/SkidSuite/tree/master/archive/skidsuite-2). Used to go by the name "SpigotProtect" so you might see some Spigot plugins using the obfuscation from this product if you look around hard enough. Can be deobfuscated using [JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator). 
* [Paramorphism](https://paramorphism.dev/) - [Discord](https://discordapp.com/invite/k9DPvEy) (Dead) - Commerical. Was one of the most unusual and unique obfuscators at the time it was an active project in that relied a lot more on the JVM's unusual way of loading JAR archives including zip entries with duplicated names and the [fake directory trick](https://github.com/x4e/fakedirectory). Used to be more commonly used before people started ripping ideas from Paramorphism. Can be deobfuscated using [JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator).
* [Popuskator](https://github.com/erxson/Popuskator) - FOSS. Obfuscator based of Ambien. 100% Skidded, nothing custom.
* [qProtect](https://mdma.dev/) - [Discord](https://discord.gg/PrxktvRTt9) - Commericial. Got [cracked](https://masterof13fps.com/forum/index.php?threads/qprotect-cracked-by-hcu.8886/#post-71519) millions of times, Devs and Admin only care about money, promotion and like to d0x people that don't like qProtect and possibly harass them or try to scare them. Horrible scam for $70 (Skidfuscator FOSS would do better).
* [Radon](https://github.com/ItzSomebody/radon) - FOSS. Abandoned experimentational obfuscator by ItsSomebody (The person that made some of the parts of this Obfuscator list). Radon is an open-source free obfuscator. It has a UI that's visually similar to Skidfuscator/ProGuard and it is very intuitive to use. Easy to deobfuscate using [JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator).
* [Sandmark](http://sandmark.cs.arizona.edu) - FOSS. Really old obfuscator research project led by Christian Collberg at the University of Arizona. Has some interesting ideas in static and dnyamic watermarking (Embeder & Recognizer) are some of the flow obfuscation ideas are good.
* [Scuti](https://github.com/netindev/scuti) - FOSS. Outdated obfuscator. Has an option to pack classes into binary blobs, and load them via a classloader. The binary blob names are just the original class names with simple XOR encryption, and the blob contents are the original class file with simple XOR encryption. Can be deobfuscated using [Narumii](https://github.com/narumii/Deobfuscator).
* [Sentinel](https://cdn.discordapp.com/attachments/972906162641076317/972942077669310556/SentinelObf-1.0-SNAPSHOT-all-obf.jar) - [Discord](https://discord.gg/y3s9qq5Q) - FOSS. Dead, Obfuscator mainly known in Minecraft community. Has some basic features. Currently there are no public transformers for it and still can be used. If you decide to use it make sure to use key "sentinelisback" once you run it in cmd.
* [Skidfusctor](https://github.com/skidfuscatordev/skidfuscator-java-obfuscator) - [Discord](https://discord.gg/srFPwUPFX3) - FOSS/Commericial. Skidfuscator is known obfuscator for its simplicity, ease of use, and effectiveness in protecting Java applications from reverse engineering and tampering. You can get free version having overall strong obfuscation. Paid (Enterprises) version has Native obfuscation with some other features. Has it's own [documentary website](https://skidfuscator.dev/docs/). Requires libraries (Doesn't have max depth). Free version has slightly broken Matcher. Uses [Maple IR](https://github.com/LLVM-but-worse/maple-ir) framework which is something worth checking out. Shows alot in Minecraft community.
* [Souvenir](https://github.com/Body-Alhoha/Souvenir) - FOSS. Lightweight obfuscation that doesn't have anything special. Has only 3 transformers (Light Flow, String, Number).
* [Stringer](https://jfxstore.com/stringer/) - Commericial. Pretty infamous for its complicated AES-based encryption/decryption routines and price. Does not really offer a whole lot of protection, but sometimes does show up in industry. Can be deobfuscated using [JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator) and got cracked few times.
* [Virbox Protector](https://lm.virbox.com/product/8.html) - Commercial. A native obfuscator, has a code virtualization made by chinese ppl. It's very different from native obfuscators from github and it's very expensive, almost 10k CNY per year.
* [XenonGuard](https://github.com/darklol9/Some-Java-Obfuscator) - FOSS. XenonGuard is a somewhat decent obfuscator based off CheatBreaker. Kinda looks like free version of ZKM. Has a very good and usefull features that not every obfuscator has these days. Even tho there are no public deobfuscation transformers, I still recommend layering it since it's based off CheatBreaker and im unsure if some transformer are still from CheatBreaker. Overall i really like this one.
* [yGuard](https://www.yworks.com/products/yguard) - FOSS. Functionally equivalent to ProGuard as far as I can tell.
* [zProtect](https://github.com/JessSystemV/zProtect) - [Discord](https://discord.com/invite/dnGKGuwvGH) - Commercial. Stupid Binscure skid. Not recomended for use. SRC of it has been leaked and their obfuscation could be possibly deobfuscated using [darklols](https://github.com/darklol9) zProtect deobfuscator or using Binscure deobfuscator to semi deobfuscate it.
* [ZKM (Zelix Klass Master)](https://zelix.com/klassmaster/index.html) - Commericial. Zelix KlassMaster Obfuscator is known for its robust obfuscation techniques and strong obfuscation capabilities and is used by many companies to protect their Java applications from reverse engineering and tampering. Currently the best obfuscator for Java right now and always drops a insane update to patch stuff whenever there are public deobfuscation transformers.
* [Zortfuscator (Discord)](https://discord.gg/A3wsGKWGSc) - Commericial. Dead, not so known obfuscator. Can tell that it has good obfuscation techniques from the look at the samples they have on their discord server and some small sample in a video made by [akita](https://www.youtube.com/watch?v=0B9SPdt75JQ).
