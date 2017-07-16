---- Minecraft Crash Report ----
// Sorry :(

Time: 7/16/17 10:21 PM
Description: Exception ticking world

java.lang.ClassCastException: com.rwtema.extrautils.tileentity.enderconstructor.TileEnderPillar cannot be cast to crazypants.enderio.machine.light.TileLightNode
	at crazypants.enderio.machine.light.BlockLightNode.func_149674_a(BlockLightNode.java:79)
	at net.minecraft.world.WorldServer.func_147456_g(WorldServer.java:569)
	at net.minecraft.world.WorldServer.func_72835_b(WorldServer.java:288)
	at net.minecraft.server.MinecraftServer.func_71190_q(MinecraftServer.java:931)
	at net.minecraft.server.dedicated.DedicatedServer.func_71190_q(DedicatedServer.java:431)
	at net.minecraft.server.MinecraftServer.func_71217_p(MinecraftServer.java:809)
	at net.minecraft.server.MinecraftServer.run(MinecraftServer.java:669)
	at java.lang.Thread.run(Unknown Source)


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Stacktrace:
	at crazypants.enderio.machine.light.BlockLightNode.func_149674_a(BlockLightNode.java:79)
	at net.minecraft.world.WorldServer.func_147456_g(WorldServer.java:569)
	at net.minecraft.world.WorldServer.func_72835_b(WorldServer.java:288)

-- Affected level --
Details:
	Level name: world
	All players: 0 total; []
	Chunk stats: ServerChunkCache: 687 Drop: 0
	Level seed: 4123537100932208619
	Level generator: ID 00 - default, ver 1. Features enabled: true
	Level generator options: BIOMESOP
	Level spawn location: World: (90,71,-62), Chunk: (at 10,4,2 in 5,-4; contains blocks 80,0,-64 to 95,255,-49), Region: (0,-1; contains chunks 0,-32 to 31,-1, blocks 0,0,-512 to 511,255,-1)
	Level time: 282121368 game time, 295672018 day time
	Level dimension: 0
	Level storage version: 0x04ABD - Anvil
	Level weather: Rain time: 95420 (now: false), thunder time: 6668 (now: false)
	Level game mode: Game mode: survival (ID 0). Hardcore: false. Cheats: false
Stacktrace:
	at net.minecraft.server.MinecraftServer.func_71190_q(MinecraftServer.java:931)
	at net.minecraft.server.dedicated.DedicatedServer.func_71190_q(DedicatedServer.java:431)
	at net.minecraft.server.MinecraftServer.func_71217_p(MinecraftServer.java:809)
	at net.minecraft.server.MinecraftServer.run(MinecraftServer.java:669)
	at java.lang.Thread.run(Unknown Source)

-- System Details --
Details:
	Minecraft Version: 1.7.10
	KCauldron Version: pw.prok:KCauldron:1.7.10-1614.201 Official
	Plugins: VaultRank, WorldEdit, HealthBar, GetStaff, Essentials, , WorldGuard, EssentialsProtect, EssentialsChat, EssentialsAntiBuild, iConomy, PermissionsEx, TreeAssist, Vault, EssentialsSpawn, Jobs, LWC, Marriage, Vote, ChestShop, PlotMe, Multiverse-Core, Multiverse-Inventories, Multiverse-SignPortals, Multiverse-Portals, MyPet
	Disabled Plugins: BetterChairs, , , , , , , , , , , , , , , , , , , , 
	Operating System: Windows Server 2012 R2 (amd64) version 6.3
	Java Version: 1.8.0_131, Oracle Corporation
	Java VM Version: Java HotSpot(TM) 64-Bit Server VM (mixed mode), Oracle Corporation
	Memory: 5554932888 bytes (5297 MB) / 10023862272 bytes (9559 MB) up to 10023862272 bytes (9559 MB)
	JVM Flags: 2 total; -Xms8G -Xmx10G
	AABB Pool Size: 0 (0 bytes; 0 MB) allocated, 0 (0 bytes; 0 MB) used
	IntCache: cache: 0, tcache: 44199, allocated: 15, tallocated: 103
	FML: MCP v9.05 FML v7.10.99.99 Minecraft Forge 10.13.4.1614 177 mods loaded, 172 mods active
	States: 'U' = Unloaded 'L' = Loaded 'C' = Constructed 'H' = Pre-initialized 'I' = Initialized 'J' = Post-initialized 'A' = Available 'D' = Disabled 'E' = Errored
	UCHIJAAAA	mcp{9.05} [Minecraft Coder Pack] (minecraft.jar) 
	UCHIJAAAA	FML{7.10.99.99} [Forge Mod Loader] (KCauldron-1.7.10-1614.201.jar) 
	UCHIJAAAA	Forge{10.13.4.1614} [Minecraft Forge] (KCauldron-1.7.10-1614.201.jar) 
	UCHIJAAAA	kimagine{0.2} [KImagine] (minecraft.jar) 
	UCHIJAAAA	appliedenergistics2-core{rv3-beta-6} [Applied Energistics 2 Core] (minecraft.jar) 
	UCHIJAAAA	CodeChickenCore{1.0.7.47} [CodeChicken Core] (minecraft.jar) 
	UCHIJAAAA	NotEnoughItems{1.0.5.120} [Not Enough Items] (NotEnoughItems-1.7.10-1.0.5.120-universal.jar) 
	UCHIJAAAA	ThE-core{1.0.0.1} [Thaumic Energistics Core] (minecraft.jar) 
	UCHIJAAAA	ThaumicTinkerer-preloader{0.1} [Thaumic Tinkerer Core] (minecraft.jar) 
	UCHIJAAAA	ChocoPatcher{1.1} [Choco Patcher] (minecraft.jar) 
	UCHIJAAAA	OpenModsCore{0.9.1} [OpenModsCore] (minecraft.jar) 
	UCHIJAAAA	<CoFH ASM>{000} [CoFH ASM] (minecraft.jar) 
	UCHIJAAAA	BinniePatcher{1.7.1} [Binnie Patcher] (minecraft.jar) 
	UCHIJAAAA	debug{1.0} [debug] (denseores-1.6.2.jar) 
	UCHIJAAAA	IC2{2.2.827-experimental} [IndustrialCraft 2] (industrialcraft-2-2.2.827-experimental.jar) 
	UCHIJAAAA	AdvancedSolarPanel{1.7.10-3.5.1} [Advanced Solar Panels] (AdvancedSolarPanel-1.7.10-3.5.1.jar) 
	UCHIJAAAA	AgriCraft{1.7.10-1.5.0} [AgriCraft] (AgriCraft-1.7.10-1.5.0.jar) 
	UCHIJAAAA	appliedenergistics2{rv3-beta-6} [Applied Energistics 2] (appliedenergistics2-rv3-beta-6.jar) 
	UCHIJAAAA	AWWayofTime{v1.3.3} [Blood Magic: Alchemical Wizardry] (BloodMagic-1.7.10-1.3.3-17.jar) 
	UCHIJAAAA	Baubles{1.0.1.10} [Baubles] (Baubles-1.7.10-1.0.1.10.jar) 
	UCHIJAAAA	Thaumcraft{4.2.3.5} [Thaumcraft] (Thaumcraft-1.7.10-4.2.3.5.jar) 
	UCHIJAAAA	Botania{r1.8-249} [Botania] (Botania r1.8-249.jar) 
	UCHIJAAAA	Avaritia{1.11} [Avaritia] (Avaritia-1.11.jar) 
	UCHIJAAAA	bdlib{1.9.4.109} [BD Lib] (bdlib-1.9.4.109-mc1.7.10.jar) 
	UCHIJAAAA	BiblioCraft{1.11.7} [BiblioCraft] (BiblioCraft[v1.11.7][MC1.7.10].jar) 
	UCHIJAAAA	Mantle{1.7.10-0.3.2.jenkins191} [Mantle] (Mantle-1.7.10-0.3.2b.jar) 
	UCHIJAAAA	Natura{2.2.0} [Natura] (natura-1.7.10-2.2.0.1.jar) 
	UCHIJAAAA	BiomesOPlenty{2.1.0} [Biomes O' Plenty] (BiomesOPlenty-1.7.10-2.1.0.2027-universal.jar) 
	UCHIJAAAA	BiblioWoodsBoP{1.9} [BiblioWoods Biomes O'Plenty Edition] (BiblioWoods[BiomesOPlenty][v1.9].jar) 
	UCHIJAAAA	CoFHCore{1.7.10R3.1.4} [CoFH Core] (CoFHCore-[1.7.10]3.1.4-329.jar) 
	UCHIJAAAA	Forestry{4.2.16.64} [Forestry for Minecraft] (forestry_1.7.10-4.2.16.64.jar) 
	UCHIJAAAA	BiblioWoodsForestry{1.7} [BiblioWoods Forestry Edition] (BiblioWoods[Forestry][v1.7].jar) 
	UCHIJAAAA	BiblioWoodsNatura{1.5} [BiblioWoods Natura Edition] (BiblioWoods[Natura][v1.5].jar) 
	UCHIJAAAA	ThermalFoundation{1.7.10R1.2.6} [Thermal Foundation] (ThermalFoundation-[1.7.10]1.2.6-118.jar) 
	UCHIJAAAA	ThermalExpansion{1.7.10R4.1.5} [Thermal Expansion] (ThermalExpansion-[1.7.10]4.1.5-248.jar) 
	UCHIJAAAA	BigReactors{0.4.3A} [Big Reactors] (BigReactors-0.4.3A.jar) 
	UCHIJAAAA	BinnieCore{2.0-pre14} [Binnie Core] (binnie-mods-2.0-pre14.jar) 
	UCHIJAAAA	Botany{2.0-pre14} [Botany] (binnie-mods-2.0-pre14.jar) 
	UCHIJAAAA	ExtraBees{2.0-pre14} [Extra Bees] (binnie-mods-2.0-pre14.jar) 
	UCHIJAAAA	ExtraTrees{2.0-pre14} [Extra Trees] (binnie-mods-2.0-pre14.jar) 
	UCHIJAAAA	Genetics{2.0-pre14} [Genetics] (binnie-mods-2.0-pre14.jar) 
	UCHIJAAAA	BrandonsCore{1.0.0.12} [Brandon's Core] (BrandonsCore-1.0.0.12.jar) 
	UCHIJAAAA	BuildCraft|Core{7.1.22} [BuildCraft] (buildcraft-7.1.22.jar) 
	UCHIJAAAA	BuildCraft|Transport{7.1.22} [BC Transport] (buildcraft-7.1.22.jar) 
	UCHIJAAAA	BuildCraft|Factory{7.1.22} [BC Factory] (buildcraft-7.1.22.jar) 
	UCHIJAAAA	BuildCraft|Silicon{7.1.22} [BC Silicon] (buildcraft-7.1.22.jar) 
	UCHIJAAAA	BuildCraft|Robotics{7.1.22} [BC Robotics] (buildcraft-7.1.22.jar) 
	UCHIJAAAA	BuildCraft|Energy{7.1.22} [BC Energy] (buildcraft-7.1.22.jar) 
	UCHIJAAAA	BuildCraft|Builders{7.1.22} [BC Builders] (buildcraft-7.1.22.jar) 
	UCHIJAAAA	BuildCraft|Compat{7.1.5} [BuildCraft Compat] (buildcraft-compat-7.1.5.jar) 
	UCHIJAAAA	Railcraft{9.12.2.0} [Railcraft] (Railcraft_1.7.10-9.12.2.0.jar) 
	UCHIJAAAA	TwilightForest{2.3.7} [The Twilight Forest] (twilightforest-1.7.10-2.3.7.jar) 
	UCHIJAAAA	ForgeMultipart{1.2.0.345} [Forge Multipart] (ForgeMultipart-1.7.10-1.2.0.345-universal.jar) 
	UCHIJAAAA	chisel{2.9.5.11} [Chisel] (Chisel-2.9.5.11.jar) 
	UCHIJAAAA	CarpentersBlocks{3.3.8.1} [Carpenter's Blocks] (Carpenter's Blocks v3.3.8.1 - MC 1.7.10.jar) 
	UCHIJAAAA	ComputerCraft{1.75} [ComputerCraft] (ComputerCraft1.75.jar) 
	UCHIJAAAA	customnpcs{1.7.10d} [CustomNpcs] (CustomNPCs_1.7.10d(21feb16).jar) 
	UCHIJAAAA	PTRModelLib{1.0.0} [PTRModelLib] (Decocraft-2.4.2_1.7.10.jar) 
	UCHIJAAAA	props{2.4.2} [Decocraft] (Decocraft-2.4.2_1.7.10.jar) 
	UCHIJAAAA	DraconicEvolution{1.0.2h} [Draconic Evolution] (Draconic-Evolution-1.7.10-1.0.2h.jar) 
	UCHIJAAAA	endercore{1.7.10-0.2.0.39_beta} [EnderCore] (EnderCore-1.7.10-0.2.0.39_beta.jar) 
	UCHIJAAAA	MineFactoryReloaded{1.7.10R2.8.1} [MineFactory Reloaded] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UCHIJAAAA	Waila{1.5.10} [Waila] (Waila-1.5.10_1.7.10.jar) 
	UCHIJAAAA	EnderIO{1.7.10-2.3.0.429_beta} [Ender IO] (EnderIO-1.7.10-2.3.0.429_beta.jar) 
	UCHIJAAAA	EnderStorage{1.4.7.37} [EnderStorage] (EnderStorage-1.7.10-1.4.7.37-universal.jar) 
	UCHIJAAAA	EnderTech{1.7.10-0.3.2.405} [EnderTech] (EnderTech-1.7.10-0.3.2.405.jar) 
	UCHIJAAAA	EnderZoo{1.7.10-1.0.15.32} [Ender Zoo] (EnderZoo-1.7.10-1.0.15.32.jar) 
	UCHIJAAAA	extracells{2.3.14} [Extra Cells 2] (ExtraCells-1.7.10-2.3.14b197.jar) 
	UCHIJAAAA	ExtraUtilities{1.2.12} [Extra Utilities] (extrautilities-1.2.12.jar) 
	UCHIJAAAA	harvestcraft{1.7.10j} [Pam's HarvestCraft] (Pam's HarvestCraft 1.7.10Lb.jar) 
	UCHIJAAAA	ImmersiveEngineering{0.7.7} [Immersive Engineering] (ImmersiveEngineering-0.7.7.jar) 
	UCHIJAAAA	TConstruct{1.7.10-1.8.8.build988} [Tinkers' Construct] (TConstruct-1.7.10-1.8.8.jar) 
	UCHIJAAAA	ExtraTiC{1.4.6} [ExtraTiC] (ExtraTiC-1.7.10-1.4.6.jar) 
	UCHIJAAAA	fc-dummy{0} [fc-dummy] (fastcraft-1.23.jar) 
	UCHIJAAAA	fastleafdecay{1.4} [Fast Leaf Decay] (FastLeafDecay-1.7.10-1.4.jar) 
	UCHIJAAAA	ThaumicTinkerer{unspecified} [Thaumic Tinkerer] (ThaumicTinkerer-2.5-1.7.10-512.jar) 
	UCHIJAAAA	ForbiddenMagic{1.7.10-0.575} [Forbidden Magic] (Forbidden Magic-1.7.10-0.575.jar) 
	UCHIJAAAA	ForgeIRC{1.2.9} [ForgeIRC] (ForgeIRC-1.7.10-1.2.9.jar) 
	UCHIJAAAA	MineTweaker3{3.0.10} [MineTweaker 3] (MineTweaker3-1.7.10-3.0.10B.jar) 
	UCHIJAAAA	FTBL{1.0.18.2} [FTBLib] (FTBLib-1.7.10-1.0.18.3.jar) 
	UCHIJAAAA	FTBT{1.0.2} [FTB Tweaks] (FTBTweaks-1.0.2.jar) 
	UCHIJAAAA	FTBU{1.0.18.2} [FTBUtilities] (FTBUtilities-1.7.10-1.0.18.3.jar) 
	UCHIJAAAA	funkylocomotion{1.0} [Funky Locomotion] (funky-locomotion-1.7.10-beta-7.jar) 
	UCHIJAAAA	RedstoneArsenal{1.7.10R1.1.2} [Redstone Arsenal] (RedstoneArsenal-[1.7.10]1.1.2-92.jar) 
	UCHIJAAAA	MagicBees{2.4.3} [Magic Bees] (magicbees-1.7.10-2.4.3.jar) 
	UCHIJAAAA	gendustry{1.6.3.132} [GenDustry] (gendustry-1.6.3.132-mc1.7.10.jar) 
	UCHIJAAAA	GraviSuite{1.7.10-2.0.3} [Graviation Suite] (GraviSuite-1.7.10-2.0.3.jar) 
	UCHIJAAAA	guideapi{1.7.10-1.0.1-29} [Guide-API] (Guide-API-1.7.10-1.0.1-29.jar) 
	UCHIJAAAA	iChunUtil{4.2.3} [iChunUtil] (iChunUtil-4.2.3.jar) 
	UCHIJAAAA	Hats{4.0.1} [Hats] (Hats-4.0.1.jar) 
	UCHIJAAAA	HatStand{4.0.0} [HatStand] (HatStand-4.0.0.jar) 
	UCHIJAAAA	headcrumbs{1.7.4} [Headcrumbs] (Headcrumbs-1.7.4.jar) 
	UCHIJAAAA	IC2NuclearControl{2.4.2a} [Nuclear Control 2] (IC2NuclearControl-2.4.2a.jar) 
	UCHIJAAAA	immersiveintegration{0.6.8} [Immersive Integration] (immersiveintegration-0.6.8.jar) 
	UCHIJAAAA	inpure|core{1.7.10R1.0.0B9} [INpureCore] (INpureCore-[1.7.10]1.0.0B9-62.jar) 
	UCHIJAAAA	inventorytweaks{1.59-dev-152-cf6e263} [Inventory Tweaks] (InventoryTweaks-1.59-dev-152.jar) 
	UCHIJAAAA	IronChest{6.0.62.742} [Iron Chest] (ironchest-1.7.10-6.0.62.742-universal.jar) 
	UCHIJAAAA	JABBA{1.2.2} [JABBA] (Jabba-1.2.2_1.7.10.jar) 
	UCHIJAAAA	journeymap{5.1.4p2} [JourneyMap] (journeymap-1.7.10-5.1.4p2-unlimited.jar) 
	UCHIJAAAA	LogisticsPipes{0.9.3.132} [Logistics Pipes] (logisticspipes-0.9.3.132.jar) 
	UCHIJAAAA	MineFactoryReloaded|CompatAppliedEnergistics{1.7.10R2.8.1} [MFR Compat: Applied Energistics] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UCHIJAAAA	MineFactoryReloaded|CompatBuildCraft{1.7.10R2.8.1} [MFR Compat: BuildCraft] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UCHIJAAAA	MineFactoryReloaded|CompatForestry{1.7.10R2.8.1} [MFR Compat: Forestry] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UCHIJAAAA	MineFactoryReloaded|CompatForgeMicroblock{1.7.10R2.8.1} [MFR Compat: ForgeMicroblock] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UCHIJAAAA	MineFactoryReloaded|CompatIC2{1.7.10R2.8.1} [MFR Compat: IC2] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UCHIJAAAA	MrTJPCoreMod{1.1.0.33} [MrTJPCore] (MrTJPCore-1.7.10-1.1.0.33-universal.jar) 
	UCHIJAAAA	ProjRed|Core{4.7.0pre12.95} [ProjectRed Core] (ProjectRed-1.7.10-4.7.0pre12.95-Base.jar) 
	UCHIJAAAA	ProjRed|Exploration{4.7.0pre12.95} [ProjectRed Exploration] (ProjectRed-1.7.10-4.7.0pre12.95-World.jar) 
	UCHIJAAAA	MineFactoryReloaded|CompatProjRed{1.7.10R2.8.1} [MFR Compat ProjectRed] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UCHIJAAAA	MineFactoryReloaded|CompatRailcraft{1.7.10R2.8.1} [MFR Compat: Railcraft] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UCHIJAAAA	MineFactoryReloaded|CompatThaumcraft{1.7.10R2.8.1} [MFR Compat: Thaumcraft] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UCHIJAAAA	MineFactoryReloaded|CompatThermalExpansion{1.7.10R2.8.1} [MFR Compat: Thermal Expansion] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UCHIJAAAA	MineFactoryReloaded|CompatTConstruct{1.7.10R2.8.1} [MFR Compat: Tinkers' Construct] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UCHIJAAAA	MineFactoryReloaded|CompatTwilightForest{1.7.10R2.8.1} [MFR Compat: TwilightForest] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UCHIJAAAA	MineFactoryReloaded|CompatVanilla{1.7.10R2.8.1} [MFR Compat: Vanilla] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UCHIJAAAA	modtweaker2{0.9.6} [Mod Tweaker 2] (ModTweaker2-0.9.6.jar) 
	UCHIJAAAA	Morpheus{1.7.10-1.6.21} [Morpheus] (Morpheus-1.7.10-1.6.21.jar) 
	UCHIJAAAA	Mystcraft{0.12.3.04} [Mystcraft] (mystcraft-1.7.10-0.12.3.04.jar) 
	UCHIJAAAA	NEIAddons{1.12.14.40} [NEI Addons] (neiaddons-1.12.14.40-mc1.7.10.jar) 
	UCHIJAAAA	NEIAddons|Developer{1.12.14.40} [NEI Addons: Developer Tools] (neiaddons-1.12.14.40-mc1.7.10.jar) 
	UCHIJAAAA	NEIAddons|AppEng{1.12.14.40} [NEI Addons: Applied Energistics 2] (neiaddons-1.12.14.40-mc1.7.10.jar) 
	UCHIJAAAA	NEIAddons|Botany{1.12.14.40} [NEI Addons: Botany] (neiaddons-1.12.14.40-mc1.7.10.jar) 
	UCHIJAAAA	NEIAddons|Forestry{1.12.14.40} [NEI Addons: Forestry] (neiaddons-1.12.14.40-mc1.7.10.jar) 
	UCHIJAAAA	NEIAddons|CraftingTables{1.12.14.40} [NEI Addons: Crafting Tables] (neiaddons-1.12.14.40-mc1.7.10.jar) 
	UCHIJAAAA	NEIAddons|ExNihilo{1.12.14.40} [NEI Addons: Ex Nihilo] (neiaddons-1.12.14.40-mc1.7.10.jar) 
	UCHIJAAAA	neiintegration{1.1.2} [NEI Integration] (NEIIntegration-MC1.7.10-1.1.2.jar) 
	UCHIJAAAA	NetherOres{1.7.10R2.3.1} [Nether Ores] (NetherOres-[1.7.10]2.3.1-22.jar) 
	UCHIJAAAA	neresources{0.1.0.ManuallyBuilt} [Not Enough Resources] (NotEnoughResources-1.7.10-0.1.0-128.jar) 
	UCHIJAAAA	OpenMods{0.9.1} [OpenMods] (OpenModsLib-1.7.10-0.9.1.jar) 
	UCHIJAAAA	OpenBlocks{1.5.1} [OpenBlocks] (OpenBlocks-1.7.10-1.5.1.jar) 
	UCHIJAAAA	OpenPeripheralCore{1.3} [OpenPeripheralCore] (OpenPeripheralCore-1.7.10-1.3.jar) 
	UCHIJAAAA	OpenPeripheral{0.5.1} [OpenPeripheralAddons] (OpenPeripheralAddons-1.7.10-0.5.1.jar) 
	UCHIJAAAA	OpenPeripheralIntegration{0.5} [OpenPeripheralIntegration] (OpenPeripheralIntegration-1.7.10-0.5.jar) 
	UCHIJAAAA	ProjRed|Transmission{4.7.0pre12.95} [ProjectRed Transmission] (ProjectRed-1.7.10-4.7.0pre12.95-Integration.jar) 
	UCHIJAAAA	ProjRed|Transportation{4.7.0pre12.95} [ProjectRed Transportation] (ProjectRed-1.7.10-4.7.0pre12.95-Mechanical.jar) 
	UCHIJAAAA	ProjRed|Compatibility{4.7.0pre12.95} [ProjectRed Compatibility] (ProjectRed-1.7.10-4.7.0pre12.95-Compat.jar) 
	UCHIJAAAA	ProjRed|Integration{4.7.0pre12.95} [ProjectRed Integration] (ProjectRed-1.7.10-4.7.0pre12.95-Integration.jar) 
	UCHIJAAAA	ProjRed|Illumination{4.7.0pre12.95} [ProjectRed Illumination] (ProjectRed-1.7.10-4.7.0pre12.95-Lighting.jar) 
	UCHIJAAAA	ProjRed|Expansion{4.7.0pre12.95} [ProjectRed Expansion] (ProjectRed-1.7.10-4.7.0pre12.95-Mechanical.jar) 
	UCHIJAAAA	rftools{4.23} [RFTools] (rftools-4.23.jar) 
	UCHIJAAAA	SolarExpansion{1.6a} [Solar Expansion] (SolarExpansion-Basic-1.6a.jar) 
	UCHIJAAAA	springboards{0.1} [Spring Boards] (Springboards-1.7.10-0.1.jar) 
	UCHIJAAAA	StevesFactoryManager{A93} [Steve's Factory Manager] (StevesFactoryManagerA93.jar) 
	UCHIJAAAA	StevesAddons{0.10.16} [Steve's Addons] (StevesAddons-1.7.10-0.10.16.jar) 
	UCHIJAAAA	StevesCarts{2.0.0.b18} [Steve's Carts 2] (StevesCarts2.0.0.b18.jar) 
	UCHIJAAAA	StevesWorkshop{0.5.1} [Steve's Workshop] (StevesWorkshop-0.5.1.jar) 
	UCHIJAAAA	StorageDrawers{1.7.10-1.10.8} [Storage Drawers] (StorageDrawers-1.7.10-1.10.8.jar) 
	UCHIJAAAA	StorageDrawersBop{1.7.10-1.1.1} [Storage Drawers: Biomes O' Plenty Pack] (StorageDrawers-BiomesOPlenty-1.7.10-1.1.1.jar) 
	UCHIJAAAA	StorageDrawersForestry{1.7.10-1.1.2} [Storage Drawers: Forestry Pack] (StorageDrawers-Forestry-1.7.10-1.1.2.jar) 
	UCHIJAAAA	StorageDrawersMisc{1.7.10-1.1.2} [Storage Drawers: Misc Pack] (StorageDrawers-Misc-1.7.10-1.1.2.jar) 
	UCHIJAAAA	StorageDrawersNatura{1.7.10-1.1.1} [Storage Drawers: Natura Pack] (StorageDrawers-Natura-1.7.10-1.1.1.jar) 
	UCHIJAAAA	tcinventoryscan{1.0.11} [TC Inventory Scanning] (tcinventoryscan-mc1.7.10-1.0.11.jar) 
	UCHIJAAAA	thaumcraftneiplugin{@VERSION@} [Thaumcraft NEI Plugin] (thaumcraftneiplugin-1.7.10-1.7a.jar) 
	UCHIJAAAA	thaumicenergistics{1.0.0.4} [Thaumic Energistics] (thaumicenergistics-1.0.0.4.jar) 
	UCHIJAAAA	ThaumicExploration{0.6.0} [Thaumic Exploration] (ThaumicExploration-1.7.10-1.1-53.jar) 
	UCHIJAAAA	ThermalDynamics{1.7.10R1.1.0} [Thermal Dynamics] (ThermalDynamics-[1.7.10]1.1.0-161.jar) 
	UCHIJAAAA	TiCTooltips{1.2.5} [TiC Tooltips] (TiCTooltips-mc1.7.10-1.2.5.jar) 
	UCHIJAAAA	TMechworks{0.2.15.106} [Tinkers' Mechworks] (TMechworks-1.7.10-0.2.15.106.jar) 
	UCHIJAAAA	Translocator{1.1.2.16} [Translocator] (Translocator-1.7.10-1.1.2.16-universal.jar) 
	UCHIJAAAA	WailaHarvestability{1.1.6} [Waila Harvestability] (WailaHarvestability-mc1.7.10-1.1.6.jar) 
	UCHIJAAAA	wawla{1.3.1} [What Are We Looking At] (Wawla-1.0.5.120.jar) 
	UCHIJAAAA	witchery{0.24.1} [Witchery] (witchery-1.7.10-0.24.1.jar) 
	UCHIJAAAA	WR-CBE|Core{1.4.1.9} [WR-CBE Core] (WR-CBE-1.7.10-1.4.1.9-universal.jar) 
	UCHIJAAAA	WR-CBE|Addons{1.4.1.9} [WR-CBE Addons] (WR-CBE-1.7.10-1.4.1.9-universal.jar) 
	UCHIJAAAA	WR-CBE|Logic{1.4.1.9} [WR-CBE Logic] (WR-CBE-1.7.10-1.4.1.9-universal.jar) 
	UCHIJAAAA	McMultipart{1.2.0.345} [Minecraft Multipart Plugin] (ForgeMultipart-1.7.10-1.2.0.345-universal.jar) 
	UCHIJAAAA	ForgeRelocation{0.0.1.4} [ForgeRelocation] (ForgeRelocation-1.7.10-0.0.1.4-universal.jar) 
	UCHIJAAAA	MCFrames{1.0} [MCFrames] (ForgeRelocation-1.7.10-0.0.1.4-universal.jar) 
	UCHIJAAAA	RelocationFMP{0.0.1.2} [RelocationFMP] (ForgeRelocationFMP-1.7.10-0.0.1.2-universal.jar) 
	UCHIJAAAA	aobd{2.9.2} [Another One Bites The Dust] (AOBD-2.9.2.jar) 
	UCHIJAAAA	denseores{1.0} [Dense Ores] (denseores-1.6.2.jar) 
	UCHIJAAAA	ForgeMicroblock{1.2.0.345} [Forge Microblocks] (ForgeMultipart-1.7.10-1.2.0.345-universal.jar) 
	UD	MineFactoryReloaded|CompatAtum{1.7.10R2.8.1} [MFR Compat: Atum] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UD	MineFactoryReloaded|CompatBackTools{1.7.10R2.8.1} [MFR Compat: BackTools] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UD	MineFactoryReloaded|CompatChococraft{1.7.10R2.8.1} [MFR Compat: Chococraft] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UD	MineFactoryReloaded|CompatExtraBiomes{1.7.10R2.8.1} [MFR Compat: ExtraBiomes] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	UD	MineFactoryReloaded|CompatSufficientBiomes{1.7.10R2.8.1} [MFR Compat: Sufficient Biomes] (MineFactoryReloaded-[1.7.10]2.8.1-174.jar) 
	OpenModsLib class transformers: [stencil_patches:ENABLED],[movement_callback:ENABLED],[map_gen_fix:FINISHED],[gl_capabilities_hook:ENABLED],[player_render_hook:ENABLED]
	Class transformer null safety: all safe
	AE2 Version: beta rv3-beta-6 for Forge 10.13.4.1448
	Mantle Environment: DO NOT REPORT THIS CRASH! Unsupported mods in environment: bukkit
	CoFHCore: -[1.7.10]3.1.4-329
	ThermalFoundation: -[1.7.10]1.2.6-118
	ThermalExpansion: -[1.7.10]4.1.5-248
	MineFactoryReloaded: -[1.7.10]2.8.1-174
	TConstruct Environment: Environment healthy.
	RedstoneArsenal: -[1.7.10]1.1.2-92
	NetherOres: -[1.7.10]2.3.1-22
	ThermalDynamics: -[1.7.10]1.1.0-161
	List of loaded APIs: 
		* AgriCraftAPI (1.0) from AgriCraft-1.7.10-1.5.0.jar
		* appliedenergistics2|API (rv2) from ThaumicTinkerer-2.5-1.7.10-512.jar
		* Baubles|API (1.0.1.10) from Baubles-1.7.10-1.0.1.10.jar
		* BiomesOPlentyAPI (1.0.0) from BiomesOPlenty-1.7.10-2.1.0.2027-universal.jar
		* BloodMagicAPI (1.3.3-13) from BloodMagic-1.7.10-1.3.3-17.jar
		* BotaniaAPI (61) from Avaritia-1.11.jar
		* BuildCraftAPI|blocks (1.0) from buildcraft-7.1.22.jar
		* BuildCraftAPI|blueprints (1.5) from buildcraft-7.1.22.jar
		* BuildCraftAPI|boards (2.0) from buildcraft-7.1.22.jar
		* BuildCraftAPI|core (1.0) from SolarExpansion-Basic-1.6a.jar
		* BuildCraftAPI|crops (1.1) from Railcraft_1.7.10-9.12.2.0.jar
		* BuildCraftAPI|events (2.0) from buildcraft-7.1.22.jar
		* BuildCraftAPI|facades (1.1) from buildcraft-7.1.22.jar
		* BuildCraftAPI|filler (4.0) from buildcraft-7.1.22.jar
		* BuildCraftAPI|fuels (2.0) from buildcraft-7.1.22.jar
		* BuildCraftAPI|gates (4.1) from buildcraft-7.1.22.jar
		* BuildCraftAPI|items (1.1) from buildcraft-7.1.22.jar
		* BuildCraftAPI|library (2.0) from buildcraft-7.1.22.jar
		* BuildCraftAPI|lists (1.0) from Railcraft_1.7.10-9.12.2.0.jar
		* BuildCraftAPI|power (1.3) from buildcraft-7.1.22.jar
		* BuildCraftAPI|recipes (3.0) from buildcraft-7.1.22.jar
		* BuildCraftAPI|robotics (3.0) from buildcraft-7.1.22.jar
		* BuildCraftAPI|statements (1.1) from Railcraft_1.7.10-9.12.2.0.jar
		* BuildCraftAPI|tablet (1.0) from Railcraft_1.7.10-9.12.2.0.jar
		* BuildCraftAPI|tiles (1.2) from buildcraft-7.1.22.jar
		* BuildCraftAPI|tools (1.0) from SolarExpansion-Basic-1.6a.jar
		* BuildCraftAPI|transport (4.1) from Railcraft_1.7.10-9.12.2.0.jar
		* CarpentersBlocks|API (3.3.7) from Carpenter's Blocks v3.3.8.1 - MC 1.7.10.jar
		* ChiselAPI (0.1.1) from Chisel-2.9.5.11.jar
		* ChiselAPI|Carving (0.1.1) from Chisel-2.9.5.11.jar
		* ChiselAPI|Rendering (0.1.1) from Chisel-2.9.5.11.jar
		* CoFHAPI (1.7.10R1.0.13B2) from CoFHLib-[1.7.10]1.2.1-185.jar
		* CoFHAPI|block (1.7.10R1.0.13) from EnderIO-1.7.10-2.3.0.429_beta.jar
		* CoFHAPI|core (1.7.10R1.0.3) from SolarExpansion-Basic-1.6a.jar
		* CoFHAPI|energy (1.7.10R1.0.2) from IC2NuclearControl-2.4.2a.jar
		* CoFHAPI|fluid (1.7.10R1.0.13B2) from CoFHLib-[1.7.10]1.2.1-185.jar
		* CoFHAPI|inventory (1.7.10R1.0.1) from buildcraft-compat-7.1.5.jar
		* CoFHAPI|item (1.7.10R1.0.13B1) from extrautilities-1.2.12.jar
		* CoFHAPI|items (1.7.10R1.0.3) from SolarExpansion-Basic-1.6a.jar
		* CoFHAPI|modhelpers (1.7.10R1.0.13B2) from CoFHLib-[1.7.10]1.2.1-185.jar
		* CoFHAPI|tileentity (1.7.10R1.0.13B2) from CoFHLib-[1.7.10]1.2.1-185.jar
		* CoFHAPI|transport (1.7.10R1.0.13B2) from CoFHLib-[1.7.10]1.2.1-185.jar
		* CoFHAPI|world (1.7.10R1.0.13B2) from CoFHLib-[1.7.10]1.2.1-185.jar
		* CoFHLib (1.7.10R1.0.3B3) from CoFHLib-[1.7.10]1.2.1-185.jar
		* CoFHLib|audio (1.7.10R1.0.4B1) from EnderTech-1.7.10-0.3.2.405.jar
		* CoFHLib|gui (1.7.10R1.0.3B3) from CoFHLib-[1.7.10]1.2.1-185.jar
		* CoFHLib|gui|container (1.7.10R1.0.3B3) from CoFHLib-[1.7.10]1.2.1-185.jar
		* CoFHLib|gui|element (1.7.10R1.2.1) from CoFHCore-[1.7.10]3.1.4-329.jar
		* CoFHLib|gui|element|listbox (1.7.10R1.0.4B1) from EnderTech-1.7.10-0.3.2.405.jar
		* CoFHLib|gui|slot (1.7.10R1.0.4B1) from EnderTech-1.7.10-0.3.2.405.jar
		* CoFHLib|inventory (1.7.10R1.0.3B3) from CoFHLib-[1.7.10]1.2.1-185.jar
		* CoFHLib|render (1.7.10R1.0.3B3) from CoFHLib-[1.7.10]1.2.1-185.jar
		* CoFHLib|render|particle (1.7.10R1.0.4B1) from EnderTech-1.7.10-0.3.2.405.jar
		* CoFHLib|util (1.7.10R1.0.3B3) from CoFHLib-[1.7.10]1.2.1-185.jar
		* CoFHLib|util|helpers (1.7.10R1.2.1) from CoFHCore-[1.7.10]3.1.4-329.jar
		* CoFHLib|util|position (1.7.10R1.0.3B3) from CoFHLib-[1.7.10]1.2.1-185.jar
		* CoFHLib|world (1.7.10R1.0.4B1) from EnderTech-1.7.10-0.3.2.405.jar
		* CoFHLib|world|feature (1.7.10R1.2.1) from CoFHCore-[1.7.10]3.1.4-329.jar
		* ComputerCraft|API (1.75) from ComputerCraft1.75.jar
		* ComputerCraft|API|FileSystem (1.75) from ComputerCraft1.75.jar
		* ComputerCraft|API|Lua (1.75) from ComputerCraft1.75.jar
		* ComputerCraft|API|Media (1.75) from ComputerCraft1.75.jar
		* ComputerCraft|API|Peripheral (1.75) from ComputerCraft1.75.jar
		* ComputerCraft|API|Permissions (1.75) from ComputerCraft1.75.jar
		* ComputerCraft|API|Redstone (1.75) from ComputerCraft1.75.jar
		* ComputerCraft|API|Turtle (1.75) from ComputerCraft1.75.jar
		* CSLib|API (0.3.0) from Decocraft-2.4.2_1.7.10.jar
		* DraconicEvolution|API (1.2) from Draconic-Evolution-1.7.10-1.0.2h.jar
		* EnderIOAPI (0.0.2) from EnderIO-1.7.10-2.3.0.429_beta.jar
		* EnderIOAPI|Redstone (0.0.2) from EnderIO-1.7.10-2.3.0.429_beta.jar
		* EnderIOAPI|Teleport (0.0.2) from EnderIO-1.7.10-2.3.0.429_beta.jar
		* EnderIOAPI|Tools (0.0.2) from EnderIO-1.7.10-2.3.0.429_beta.jar
		* ForestryAPI|apiculture (4.8.0) from forestry_1.7.10-4.2.16.64.jar
		* ForestryAPI|arboriculture (4.2.1) from forestry_1.7.10-4.2.16.64.jar
		* ForestryAPI|circuits (3.1.0) from forestry_1.7.10-4.2.16.64.jar
		* ForestryAPI|core (5.0.0) from forestry_1.7.10-4.2.16.64.jar
		* ForestryAPI|farming (2.1.0) from forestry_1.7.10-4.2.16.64.jar
		* ForestryAPI|food (1.1.0) from forestry_1.7.10-4.2.16.64.jar
		* ForestryAPI|fuels (2.0.1) from forestry_1.7.10-4.2.16.64.jar
		* ForestryAPI|genetics (4.7.1) from forestry_1.7.10-4.2.16.64.jar
		* ForestryAPI|hives (4.1.0) from forestry_1.7.10-4.2.16.64.jar
		* ForestryAPI|lepidopterology (1.3.0) from forestry_1.7.10-4.2.16.64.jar
		* ForestryAPI|mail (3.0.0) from forestry_1.7.10-4.2.16.64.jar
		* ForestryAPI|multiblock (3.0.0) from forestry_1.7.10-4.2.16.64.jar
		* ForestryAPI|recipes (5.4.0) from forestry_1.7.10-4.2.16.64.jar
		* ForestryAPI|storage (3.0.0) from forestry_1.7.10-4.2.16.64.jar
		* ForestryAPI|world (2.1.0) from forestry_1.7.10-4.2.16.64.jar
		* ForgeRelocation|API (0.0.1.4) from ForgeRelocation-1.7.10-0.0.1.4-universal.jar
		* gendustryAPI (2.3.0) from gendustry-1.6.3.132-mc1.7.10.jar
		* Guide-API|API (1.7.10-1.0.1-29) from Guide-API-1.7.10-1.0.1-29.jar
		* IC2API (1.0) from Railcraft_1.7.10-9.12.2.0.jar
		* ImmersiveEngineering|API (1.0) from ImmersiveEngineering-0.7.7.jar
		* inpure|api (1.7) from INpureCore-[1.7.10]1.0.0B9-62.jar
		* McJtyLib (1.8.1) from mcjtylib-1.8.1.jar
		* Mystcraft|API (0.1) from mystcraft-1.7.10-0.12.3.04.jar
		* neresources|API (1.0) from NotEnoughResources-1.7.10-0.1.0-128.jar
		* NuclearControlAPI (v1.0.5) from IC2NuclearControl-2.4.2a.jar
		* OpenBlocks|API (1.1) from OpenBlocks-1.7.10-1.5.1.jar
		* OpenPeripheralAddonsApi (1.0) from OpenPeripheralAddons-1.7.10-0.5.1.jar
		* OpenPeripheralApi (3.4) from OpenPeripheralCore-1.7.10-1.3.jar
		* RailcraftAPI|bore (1.0.0) from Railcraft_1.7.10-9.12.2.0.jar
		* RailcraftAPI|carts (1.6.0) from Railcraft_1.7.10-9.12.2.0.jar
		* RailcraftAPI|core (1.5.0) from Railcraft_1.7.10-9.12.2.0.jar
		* RailcraftAPI|crafting (1.0.0) from Railcraft_1.7.10-9.12.2.0.jar
		* RailcraftAPI|electricity (2.0.0) from Railcraft_1.7.10-9.12.2.0.jar
		* RailcraftAPI|events (1.0.0) from Railcraft_1.7.10-9.12.2.0.jar
		* RailcraftAPI|fuel (1.0.0) from Railcraft_1.7.10-9.12.2.0.jar
		* RailcraftAPI|helpers (1.1.0) from Railcraft_1.7.10-9.12.2.0.jar
		* RailcraftAPI|items (1.0.0) from Railcraft_1.7.10-9.12.2.0.jar
		* RailcraftAPI|locomotive (1.1.0) from Railcraft_1.7.10-9.12.2.0.jar
		* RailcraftAPI|signals (2.3.0) from Railcraft_1.7.10-9.12.2.0.jar
		* RailcraftAPI|tracks (2.3.0) from Railcraft_1.7.10-9.12.2.0.jar
		* StorageDrawersAPI (1.7.10-1.2.0) from StorageDrawers-1.7.10-1.10.8.jar
		* StorageDrawersAPI|config (1.7.10-1.2.0) from StorageDrawers-1.7.10-1.10.8.jar
		* StorageDrawersAPI|event (1.7.10-1.2.0) from StorageDrawers-1.7.10-1.10.8.jar
		* StorageDrawersAPI|inventory (1.7.10-1.2.0) from StorageDrawers-1.7.10-1.10.8.jar
		* StorageDrawersAPI|pack (1.7.10-1.2.0) from StorageDrawers-1.7.10-1.10.8.jar
		* StorageDrawersAPI|registry (1.7.10-1.2.0) from StorageDrawers-1.7.10-1.10.8.jar
		* StorageDrawersAPI|render (1.7.10-1.2.0) from StorageDrawers-1.7.10-1.10.8.jar
		* StorageDrawersAPI|storage (1.7.10-1.2.0) from StorageDrawers-1.7.10-1.10.8.jar
		* StorageDrawersAPI|storage-attribute (1.7.10-1.2.0) from StorageDrawers-1.7.10-1.10.8.jar
		* Thaumcraft|API (4.2.2.0) from Pam's HarvestCraft 1.7.10Lb.jar
		* thaumicenergistics|API (1.1) from thaumicenergistics-1.0.0.4.jar
		* WailaAPI (1.2) from Waila-1.5.10_1.7.10.jar
	Chisel: Errors like "[FML]: Unable to lookup ..." are NOT the cause of this crash. You can safely ignore these errors. And update forge while you're at it.
	EnderIO: Found the following problem(s) with your installation:
                 An unsupported base software is installed: 'kcauldron, cauldron, craftbukkit, mcpc'. This is NOT supported.
                 This may have caused the error. Try reproducing the crash WITHOUT this/these mod(s) before reporting it.
	Forestry : Warning: You have mods that change the behavior of Minecraft, ForgeModLoader, and/or Minecraft Forge to your client: 
Bukkit, Cauldron, or other Bukkit replacement
These may have caused this error, and may not be supported. Try reproducing the crash WITHOUT these mods, and report it then.
	AE2 Integration: IC2:ON, RotaryCraft:OFF, RC:ON, BuildCraftCore:ON, BuildCraftTransport:ON, BuildCraftBuilder:ON, RF:ON, RFItem:ON, MFR:ON, DSU:ON, FZ:OFF, FMP:ON, RB:OFF, CLApi:OFF, Waila:ON, Mekanism:OFF, ImmibisMicroblocks:OFF, BetterStorage:OFF, OpenComputers:OFF, PneumaticCraft:OFF
	Profiler Position: N/A (disabled)
	Vec3 Pool Size: 0 (0 bytes; 0 MB) allocated, 0 (0 bytes; 0 MB) used
	Player Count: 0 / 20; []
	Is Modded: Definitely; Server brand changed to 'kcauldron,cauldron,craftbukkit,mcpc,fml,forge'
	Type: Dedicated Server (map_server.txt)
