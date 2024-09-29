# **Ostranauts Career Dump**

### **Crackdown** `CGEncCrackdownIntro`

* **RISK: Be A Hero (Unarmed Melee)** `CGEncCrackdownBeAHeroFail`

	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpIsImprisoned=1.0x1`
	* Condition: `TDnEncHeroFailChance=1.0x1`

* **Fake A Pressure Alarm** `CGEncCrackdownFakeAPressureAlarm`

	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillHacking=1.0x1`
	* Condition: `TUpIsGenius=1.0x1.0`

* **RISK: Be A Hero (Unarmed Melee)** `CGEncCrackdownBeAHeroSuccess`

	* Social: `CGEncHomeworldLEOEnemy`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillRangedArchery=1.0x1`
	* Condition: `TUpIsBrave=1.0x1`
	* Condition: `TDnEncHeroFailChance=1.0x1`
	* Item/Other: `CTEncRandomInjuryPastFight=1.0x1`
	* $1,750.00

* **Hide In An Air Vent** `CGEncCrackdownVents`

	* Social: `CGEncRandomAdultFriend`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillStealth=1.0x1`
	* Condition: `TUpSkillIntrusion=1.0x1`
	* Condition: `TUpIsCraven=1.0x1`
	* $246.00

* **Bluff** `CGEncCrackdownBluff`

	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillForgery=1.0x1`
	* Condition: `TUpSkillActing=1.0x1`
	* $500.00

* **Have Nothing To Hide** `CGEncCrackdownNothingToHide`

	* Social: `CGEncHomeworldRandomLEOFriend`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillEtiquetteStreet=1.0x1`
	* Condition: `TUpIsHonest=1.0x1`
	* Condition: `TUpIsArrogant=1.0x1`


### **Daily Grind** `CGEncDailyGrindIntro`

* **Watch Old Movies** `CGEncDailyGrindOldMovies`

	* Social: `CGEncHomeworldRandomManagerFriend`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpIsObservant=1.0x1.0`
	* Condition: `TUpSkillActing=1.0x1`

* **Suit Maintenance** `CGEncDailyGrindFeverishSuitMaintenance`

	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillOpsEnvSuit=1.0x1`
	* Condition: `TUpSkillSciencePhysics=1.0x1`
	* Condition: `TUpIsPatient=1.0x1`
	* Condition: `TUpIsFinicky=1.0x1`

* **Fight Club** `CGEncDailyGrindUndergroundBoxing`

	* Item/Other: `COSocialNameDropLEO`
	* Social: `CGEncHomeworldRandomLEOFriend`
	* Condition: `TUpSkillMeleeUnarmed=1.0x1`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpIsBrave=1.0x1`
	* Condition: `TUpIsMasochist=1.0x1`
	* Item/Other: `CTEncRandomInjuryPastFight=1.0x1`

* **Go Shipspotting** `CGEncDailyGrindShippingNews`

	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpIsComplacent=1.0x1`
	* Condition: `TUpSkillOpsSensors=1.0x1`
	* Condition: `TUpIsShy=1.0x1.0`
	* $650.00

* **Hacking** `CGEncDailyGrindHacking`

	* Condition: `ItmComponentMobo01=1.0x1`
	* Condition: `ItmHeatSink01=1.0x1`
	* Social: `CGEncHomeworldLEOEnemy`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillHacking=1.0x1`

* **Get a Second Job as an Electrician** `CGEncDailyGrindKioskJob`

	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpIsPatient=1.0x1.0`
	* Condition: `TUpSkillEngElectronic=1.0x1`
	* $200.00


### **Manslaughter.** `CGEncManslaughter`

* **Time in the Brig** `CGEncImprisoned`

	* Social: `CGEncHomeworldLEOEnemy`
	* Social: `CGEncHomeworldPrisonerFriend`
	* Social: `CGEncHomeworldCriminalEnemy`
	* Social: `CGEncHomeworldCriminalContact`
	* Condition: `TUpAge=1.0x1-3`
	* Condition: `TDnIsImprisoned=1.0x1`
	* Item/Other: `CTEncRandomInjuryPastFight=1.0x1-3`
	* Condition: `CareerPrisonerPast=1.0x1`
	* Condition: `TraitChronicScarCuffs=0.9x1`
	* Condition: `SkillMeleeUnarmed=0.7x1|IsQuitter=0.1x1|IsFollower=0.1x1`
	* Condition: `IsCraven=0.2x1|IsBrave=0.2x1|IsSuspicious=0.2x1|IsPushover=0.1x1`
	* Condition: `IsApathetic=0.2x1|TraitChronicScarActivism=0.15x1`
	* Condition: `SkillStealth=0.2x1|TraitChronicScarBrandThief=0.15x1`
	* Condition: `IsObservant=0.2x1|TraitChronicScarIndustrial=0.15x1`
	* Condition: `IsPatient=0.2x1|IsImpatient=0.2x1`
	* Condition: `IsTreacherous=0.1x1|IsSelfish=0.1x1|IsVengeful=0.1x1|IsAgliophobic=0.1x1`
	* Item/Other: `CONDAgingChanceRandomChronicCondition=0.5x1-3`


### **Occupational Hazard** `CGEncPodDisasterIntro`

* **Troubleshoot Engine** `CGEncPodDisasterEngSpaceship`

	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillOpsSpaceship=1.0x1`
	* $850.00

* **Hack Engine** `CGEncPodDisasterHackEngine`

	* Social: `CGEncCriminalContact`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillHacking=1.0x1`
	* Condition: `TUpIsGenius=1.0x1.0`

* **Take the Stick** `CGEncPodDisasterNavigate`

	* Social: `CGEncRandomAdultFriend`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillOpsSpaceship=1.0x1`
	* Condition: `TUpSkillOpsEnvSuit=1.0x1`
	* Item/Other: `CTEncRandomInjuryLeg=1.0x1`

* **Jury Rig Engine** `CGEncPodDisasterEngMechanical`

	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillEngMechanical=1.0x1`
	* Condition: `TUpIsBrave=1.0x1`
	* Condition: `TUpIsCoordinated=1.0x1.0`
	* $-150.00

* **RISK: Abandon ship! (EVA Suit Ops)** `CGEncPodDisasterRiskAbandonShipSuccess`

	* Item/Other: `OutfitEVA01Full=1.0x1`
	* Item/Other: `OutfitHelmet03=1.0x1`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TDnEncPodDisasterFailChance=1.0x1`

* **RISK: Abandon ship! (EVA Suit Ops)** `CGEncPodDisasterRiskAbandonShipFail`

	* Condition: `TUpAge=1.0x1`
	* Condition: `TDnEncPodDisasterFailChance=1.0x1`
	* Item/Other: `CTEncRandomInjuryBurn=1.0x1`
	* $-1,050.00


### **Poker Game** `CGEncPokerGameIntro`

* **Call Him On A Technicality** `CGEncPokerGameTechnicality`

	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillGambling=1.0x1`
	* $300.00

* **RISK: Call The Bluff (Gambling Skill)** `CGEncPokerGameCallBluffFail`

	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillGambling=1.0x1`
	* Condition: `TDnEncPokerFailChance=1.0x1`
	* $-9,000.00

* **RISK: Call The Bluff (Gambling Skill)** `CGEncPokerGameCallBluffSuccess`

	* Item/Other: `ItmShipbreakerLoadout`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillGambling=1.0x1`
	* Condition: `TDnEncPokerFailChance=1.0x1`
	* Ship: `CGEncShipbreakerPrizeShip`

* **Cheat** `CGEncPokerGameCheat`

	* Social: `CGEncHomeworldLEOEnemy`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillHacking=1.0x1`
	* Item/Other: `CTEncRandomInjuryPastFight=1.0x1`
	* $1,500.00

* **No Thanks...Fold** `CGEncPokerGameFold`

	* $900.00

* **Grab The Key And Run** `CGEncPokerGameYoink`

	* Item/Other: `ItmShipbreakerLoadout`
	* Social: `CGEncCriminalEnemy`
	* Social: `CGEncRandomEnemy`
	* Social: `CGEncRandomEnemy`
	* Condition: `TUpAge=1.0x1`
	* $-6,500.00
	* Ship: `CGEncShipbreakerPrizeShip`


### **Rare Salvage** `CGEncRareSalvageIntro`

* **Bribe Your Boss and Split the Profits** `CGEncRareSalvageBribeBoss`

	* Item/Other: `COSocialNameDropManager`
	* Social: `CGEncHomeworldLEOEnemy`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillEtiquetteOligarch=1.0x1.0`
	* $750.00

* **Notify Ayotimiwa Corporate** `CGEncRareSalvageTellAyotimiwa`

	* Condition: `OutfitTShirt05=1.0x1`
	* Social: `CGEncHomeworldManagerContact`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillAdmin=1.0x1`
	* Condition: `TUpIsFollower=1.0x1`

* **RISK: Take It For Yourself (Patient)** `CGEncRareSalvageTakeItForYourselfFail`

	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpIsImprisoned=1.0x1`
	* Condition: `TDnEncStealFailChance=1.0x1`

* **RISK: Take It For Yourself (Patient)** `CGEncRareSalvageTakeItForYourselfSuccess`

	* Condition: `ItmRCSDistro01Loose=1.0x1`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TDnEncStealFailChance=1.0x1`

* **Smuggle It Through the Blackmarket** `CGEncRareSalvageSmuggleItOffSite`

	* Item/Other: `COSocialNameDropCrim`
	* Social: `CGEncHomeworldCriminalContact`
	* Social: `CGEncHomeworldLEOEnemy`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillEtiquetteStreet=1.0x1.0`
	* $200.00

* **Smash It and Feel Alive** `CGEncRareSalvageSmash`

	* Item/Other: `ItmHydraComponents=1.0x1`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillMeleeArmed=1.0x1.0`
	* Condition: `TUpIsCruel=1.0x1.0`
	* Condition: `TUpIsPessimist=1.0x1`
	* Condition: `TUpIsStrong=1.0x1`
	* Condition: `TUpTraitChronicScarCargo=1.0x1`


### **King Incognito** `CGEncRichSchmuckIntro`

* **Seduce Them** `CGEncRichSchmuckSeduce`

	* Item/Other: `COSocialNameDropManager`
	* Social: `CGEncHomeworldManagerLoverEx`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillEtiquetteOligarch=0.4x1.0`
	* Condition: `TUpSkillCooking=1.0x1.0`
	* Condition: `TUpSkillDance=1.0x1.0`
	* Condition: `TUpIsCharismatic=1.0x1.0`
	* Condition: `TUpIsBeautiful=1.0x1.0`

* **RISK: Hack Them (Hacking)** `CGEncRichSchmuckHackPhoneFail`

	* Social: `CGEncHomeworldManagerEnemy`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpIsAmbitious=1.0x1.0`
	* Condition: `TUpIsBrave=1.0x1`
	* Condition: `TDnEncRichHackFailChance=1.0x1`
	* $2,850.00

* **RISK: Hack Them (Hacking)** `CGEncRichSchmuckHackPhone`

	* Social: `CGEncHomeworldManagerEnemy`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillEngSoftware=1.0x1.0`
	* Condition: `TUpSkillEtiquetteStreet=0.35x1.0`
	* Condition: `TUpSkillHacking=0.5x1.0`
	* Condition: `TUpSkillStealth=0.35x1.0`
	* Condition: `TUpIsAmbitious=0.4x1.0`
	* Condition: `TUpIsDiligent=0.4x1.0`
	* Condition: `TUpIsGenius=0.4x1.0`
	* Condition: `TUpIsObservant=0.4x1.0`
	* Condition: `TUpIsShy=0.4x1.0`
	* Condition: `TDnEncRichHackFailChance=1.0x1`
	* $2,850.00

* **Just Mug Them** `CGEncRichSchmuckMug`

	* Social: `CGEncHomeworldManagerEnemy`
	* Social: `CGEncHomeworldBartenderEnemy`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillMeleeArmed=0.65x1.0`
	* Condition: `TUpSkillMeleeUnarmed=0.65x1.0`
	* Condition: `TUpSkillRangedGunpowder=0.65x1.0`
	* Condition: `TUpIsBrave=0.2x1.0`
	* Condition: `TUpIsCruel=0.2x1.0`
	* Condition: `TUpIsImpatient=0.2x1.0`
	* Condition: `TUpIsStrong=1.0x1`
	* $246.00

* **Start a Riot** `CGEncRichSchmuckInciteRiot`

	* Social: `CGEncHomeworldBartenderEnemy`
	* Social: `CGEncHomeworldManagerEnemy`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillEtiquetteFolk=1.0x1`
	* Condition: `TUpSkillMeleeUnarmed=1.0x1`
	* Condition: `TUpSkillPersuade=1.0x1`
	* Condition: `TUpIsCharismatic=1.0x1`
	* Condition: `TUpIsLeader=1.0x1`
	* Item/Other: `CTEncRandomInjuryPastFight=1.0x1`
	* $246.00

* **Pick their Pocket** `CGEncRichSchmuckPickpocket`

	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillStealth=1.0x1`
	* Condition: `TUpSkillTracking=0.25x1.0`
	* Condition: `TUpIsObservant=0.5x1.0`
	* Condition: `TUpIsPatient=0.5x1.0`
	* Condition: `TUpIsSelfish=0.5x1.0`
	* $250.00

* **Get them Drunk** `CGEncRichSchmuckCorpSecrets`

	* Social: `CGEncHomeworldManagerContact`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillSong=1.0x1`
	* Condition: `TUpIsLiar=1.0x1`
	* Condition: `TUpIsSlovenly=1.0x1`
	* $850.00


### **Shady deal.** `CGEncShadyDealIntro`

* **Report to Ayotimiwa** `CGEncShadyDealReportThem`

	* Social: `CGEncHomeworldManagerContact`
	* Social: `CGEncHomeworldRandomLEOFriend`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpIsSelfish=1.0x1.0`
	* Item/Other: `ItmShirtHoodie01=1.0x1`
	* $900.00

* **Gather Intel for Cops** `CGEncShadyDealGatherIntel`

	* Social: `CGEncHomeworldRandomLEOFriend`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillEtiquetteStreet=1.0x1`
	* Condition: `TUpIsHonest=1.0x1`

* **RISK: Join the Scheme (Street Smarts)** `CGEncShadyDealJoinSuccess`

	* Condition: `TUpAge=1.0x1`
	* Condition: `TDnEncShadyDealFailChance=1.0x1`
	* $4,500.00

* **RISK: Join the Scheme (Street Smarts)** `CGEncShadyDealJoinFail`

	* Social: `CGEncRandomEnemy`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpIsImprisoned=1.0x1`
	* Condition: `TDnEncShadyDealFailChance=1.0x1`

* **Backstab Them** `CGEncShadyDealBackstab`

	* Social: `CGEncCriminalEnemy`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpIsTreacherous=1.0x1`
	* $900.00

* **Instigate Violence** `CGEncShadyDealViolence`

	* Social: `CGEncCriminalEnemy`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillMeleeArmed=1.0x1.0`
	* Condition: `TUpSkillMeleeUnarmed=1.0x1.0`
	* Condition: `TUpIsTough=1.0x1`
	* Item/Other: `CTEncRandomInjuryPastFight=1.0x1`
	* $900.00


### **Makeshift Salvage Pod.** `CGEncShipMakeshiftSalvagePodIntro`

* **Continue Career** `CGEncShipSalvagePodCont`

	* Condition: `TUpAge=1.0x1`

* **Take Ship** `CGEncShipSalvageSledTake`

	* Item/Other: `ItmShipbreakerLoadout`
	* Ship: `CGEncShipbreakerSled`


### **Hulk Salvage.** `CGEncShipPAX2020Intro`

* **Continue Career** `CGEncShipSalvagePodCont`

	* Condition: `TUpAge=1.0x1`

* **Take Ship** `CGEncShipPAX2020Take`

	* Ship: `CGEncShipbreakerPAX2020Ships`


### **Retrofitted Shipping Container.** `CGEncShipSalvageContainerPodIntro`

* **Take Ship** `CGEncShipSalvageContainerPodTake`

	* Item/Other: `ItmShipbreakerLoadout`
	* Ship: `CGEncShipbreakerContainerPod`

* **Continue Career** `CGEncShipSalvagePodCont`

	* Condition: `TUpAge=1.0x1`


### **Endurance Salvage Pod.** `CGEncShipSalvagePodEnduranceIntro`

* **Take Ship** `CGEncShipSalvagePodEnduranceTake`

	* Item/Other: `ItmShipbreakerLoadout`
	* Ship: `CGEncShipbreakerPodEndurance`

* **Continue Career** `CGEncShipSalvagePodCont`

	* Condition: `TUpAge=1.0x1`


### **Salvage Pod.** `CGEncShipSalvagePodIntro`

* **Continue Career** `CGEncShipSalvagePodCont`

	* Condition: `TUpAge=1.0x1`

* **Take Ship** `CGEncShipSalvagePodTake`

	* Item/Other: `ItmShipbreakerLoadout`
	* CGEncShipSalvagePodTake
	* Ship: `CGEncShipbreakerPod`


### **Small Salvage Pod.** `CGEncShipSalvagePodSmallIntro`

* **Continue Career** `CGEncShipSalvagePodCont`

	* Condition: `TUpAge=1.0x1`

* **Take Ship** `CGEncShipSalvagePodSmallTake`

	* Item/Other: `ItmShipbreakerLoadout`
	* Ship: `CGEncShipbreakerPodSmall`


### **Salvage Pod.** `CGEncShipSalvagePodTestIntro`

* **Continue Career** `CGEncShipSalvagePodCont`

	* Condition: `TUpAge=1.0x1`

* **Take Ship** `CGEncShipSalvagePodTestTake`

	* Item/Other: `ItmShipbreakerLoadout`
	* Ship: `CGEncShipbreakerPodTest`


### **Utility Pod.** `CGEncShipSalvageUtilityPodIntro`

* **Continue Career** `CGEncShipSalvagePodCont`

	* Condition: `TUpAge=1.0x1`

* **Take Ship** `CGEncShipSalvageUtilityPodTake`

	* Item/Other: `ItmShipbreakerLoadout`
	* Ship: `CGEncShipbreakerUtilityPod`


### **Small Shuttle.** `CGEncShipShuttleSmallIntro`

* **Take Ship** `CGEncShipShuttleSmallTake`

	* Item/Other: `ItmShipbreakerLoadout`
	* Ship: `CGEncShipbreakerShuttleSmall`

* **Continue Career** `CGEncShipSalvagePodCont`

	* Condition: `TUpAge=1.0x1`


### **Labor Barge Locker** `CGEncTestIntro`

* **RISK: Force the Lock (Strong)** `CGEncTestA`

	* Social: `CGEncShipbreakerFriend`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TDnEncLockFailChance=1.0x1`
	* Item/Other: `ItmToolLaserTorch01New=1.0x1`
	* $-200.00

* **Report Poor Security to Ayotimiwa** `CGEncTestE`

	* Condition: `ItmBackpack03=1.0x1`
	* Social: `CGEncHomeworldManagerContact`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillAdmin=1.0x1`
	* Condition: `TUpIsLoyal=1.0x1`

* **RISK: Force the Lock (Strong)** `CGEncTestAFail`

	* Condition: `TUpAge=1.0x1`
	* Condition: `TDnEncLockFailChance=1.0x1`
	* $-2,300.00

* **Cut Hole in Crate** `CGEncTestC`

	* Condition: `TUpAge=1.0x1`
	* Item/Other: `CTEncRandomInjuryBurn=1.0x1`
	* $700.00

* **Hack the Lock** `CGEncTestB`

	* Social: `CGEncShipbreakerFriend`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillHacking=1.0x1`
	* Condition: `TUpIsLeader=1.0x1`

* **Mislabel Crate** `CGEncTestD`

	* Social: `CGEncShipbreakerFriend`
	* Social: `CGEncRandomAdultFriend`
	* Condition: `TUpAge=1.0x1`
	* Condition: `TUpSkillEtiquetteStreet=1.0x1`
	* Condition: `TUpIsLeader=1.0x1`
