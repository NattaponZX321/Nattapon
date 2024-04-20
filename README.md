    while true do

          local fucku = 1

       end

    end



game:GetService("RunService").RenderStepped:connect(function()

game:GetService("CoreGui").DevConsoleMaster.DevConsoleWindow:Destroy()

for i,v in pairs(game.CoreGui:GetChildren()) do

    if v:FindFirstChild("PropertiesFrame") then

    if v:FindFirstChild("ExplorerPanel") then

    if v:FindFirstChild("SideMenu") then

             warn("DarkDex Detected")

             game.Players.LocalPlayer:kick("Do not open DarkDex")

             wait(.3)

             game:Shutdown()

             wait(0.2)Players:Toggle("Aimbot Skill", false, function(vu)

   _G.AimbotSkill = vu

 end)



 spawn(function()

   pcall(function()

   while game:GetService("RunService").RenderStepped:wait() do

      if _G.AimbotSkill then

         pcall(function()

            if game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool") and game.Players.LocalPlayer.Character[game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool").Name]:FindFirstChild("MousePos") then

                local args = {

                    [1] = game:GetService("Players"):FindFirstChild(_G.SelectP).Character.HumanoidRootPart.Position

                }

                game:GetService("Players").LocalPlayer.Character[game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))

            end

        end)

    end

   end

   end)

end)

             gamekiller()

        end

        end

        end

    end

    end)

---BLOX FRUIT

local OldWorld = false

local Sea2 = false

local ThreeWorld = false

local placeId = game.PlaceId

if placeId == 2753915549 then

   OldWorld = true

elseif placeId == 4442272183 then

   Sea2 = true

elseif placeId == 7449423635 then

   ThreeWorld = true

end

setfflag("HumanoidParallelRemoveNoPhysics", "False")

setfflag("HumanoidParallelRemoveNoPhysicsNoSimulate2", "False")

game:GetService("Players").LocalPlayer.Data.DevilFruit.Value = "Ice-Ice"



if Sea2 then

   for i,v in pairs(game:GetService("ReplicatedStorage"):GetDescendants()) do

      if v.Name == "DarkBlade" then

         v.Parent.Name = "NoobRip"

      end

   end

end

if OldWorld then

   for i,v in pairs(game:GetService("ReplicatedStorage"):GetDescendants()) do

      if v.Name == "XavierWoods_HairAccessory" then

         v.Parent.Name = "NoobRipIndra"

      end

   end

end



local db = true

game:GetService("RunService").Heartbeat:Connect(function()

    if db == true then

        game:GetService("Workspace").NoClipxd.CanCollide = false

                    wait(.5)

            db = false

        else

            game:GetService("Workspace").NoClipxd.CanCollide = true

            wait(.5)

            db = true

    end

end)

            

            

local elitequest = Instance.new('Part')

elitequest.Name = "elitequest"

elitequest.CanCollide = false

elitequest.Transparency = 1

elitequest.Anchored = true

elitequest.CFrame = CFrame.new(-5419.1708984375, 314.05883789063, -2826.1838378906)

elitequest.Parent = Workspace



function CheckQuest()

   local MyLevel = game.Players.localPlayer.Data.Level.Value

   if OldWorld then

      if MyLevel == 1 or MyLevel <= 9 then -- Bandit

         Ms = "Bandit [Lv. 5]"

         QuestName = "BanditQuest1"

         LevelQuest = 1

         NameMon = "Bandit"

         CFrameQuest = CFrame.new(1061.66699, 16.5166187, 1544.52905, -0.942978859, -3.33851502e-09, 0.332852632, 7.04340497e-09, 1, 2.99841325e-08, -0.332852632, 3.06188177e-08, -0.942978859)

         CFrameMon = CFrame.new(1199.31287, 52.2717781, 1536.91516, -0.929782331, 6.60215846e-08, -0.368109822, 3.9077392e-08, 1, 8.06501603e-08, 0.368109822, 6.06023249e-08, -0.929782331)

      elseif MyLevel == 10 or MyLevel <= 14 then -- Monkey

         Ms = "Monkey [Lv. 14]"

         QuestName = "JungleQuest"

         LevelQuest = 1

         NameMon = "Monkey"

         CFrameQuest = CFrame.new(-1604.12012, 36.8521118, 154.23732, 0.0648873374, -4.70858913e-06, -0.997892559, 1.41431883e-07, 1, -4.70933674e-06, 0.997892559, 1.64442184e-07, 0.0648873374)

         CFrameMon = CFrame.new(-1402.74609, 98.5633316, 90.6417007, 0.836947978, 0, 0.547282517, -0, 1, -0, -0.547282517, 0, 0.836947978)

      elseif MyLevel == 15 or MyLevel <= 29 then -- Gorilla

         Ms = "Gorilla [Lv. 20]"

         QuestName = "JungleQuest"

         LevelQuest = 2

         NameMon = "Gorilla"

         CFrameQuest = CFrame.new(-1604.12012, 36.8521118, 154.23732, 0.0648873374, -4.70858913e-06, -0.997892559, 1.41431883e-07, 1, -4.70933674e-06, 0.997892559, 1.64442184e-07, 0.0648873374)

         CFrameMon = CFrame.new(-1223.52808, 6.27936459, -502.292664, 0.310949147, -5.66602516e-08, 0.950426519, -3.37275488e-08, 1, 7.06501808e-08, -0.950426519, -5.40241736e-08, 0.310949147)

      elseif MyLevel == 30 or MyLevel <= 39 then -- Pirate

         Ms = "Pirate [Lv. 35]"

         QuestName = "BuggyQuest1"

         LevelQuest = 1

         NameMon = "Pirate"

         CFrameQuest = CFrame.new(-1139.59717, 4.75205183, 3825.16211, -0.959730506, -7.5857054e-09, 0.280922383, -4.06310328e-08, 1, -1.11807175e-07, -0.280922383, -1.18718916e-07, -0.959730506)

         CFrameMon = CFrame.new(-1219.32324, 4.75205183, 3915.63452, -0.966492832, -6.91238853e-08, 0.25669381, -5.21195496e-08, 1, 7.3047012e-08, -0.25669381, 5.72206496e-08, -0.966492832)

      elseif MyLevel == 40 or MyLevel <= 59 then -- Brute

         Ms = "Brute [Lv. 45]"

         QuestName = "BuggyQuest1"

         LevelQuest = 2

         NameMon = "Brute"

         CFrameQuest = CFrame.new(-1139.59717, 4.75205183, 3825.16211, -0.959730506, -7.5857054e-09, 0.280922383, -4.06310328e-08, 1, -1.11807175e-07, -0.280922383, -1.18718916e-07, -0.959730506)

         CFrameMon = CFrame.new(-1146.49646, 96.0936813, 4312.1333, -0.978175163, -1.53222057e-08, 0.207781896, -3.33316912e-08, 1, -8.31738873e-08, -0.207781896, -8.82843523e-08, -0.978175163)

      elseif MyLevel == 60 or MyLevel <= 74 then -- Desert Bandit

         Ms = "Desert Bandit [Lv. 60]"

         QuestName = "DesertQuest"

         LevelQuest = 1

         NameMon = "Desert Bandit"

         CFrameQuest = CFrame.new(897.031128, 6.43846416, 4388.97168, -0.804044724, 3.68233266e-08, 0.594568789, 6.97835176e-08, 1, 3.24365246e-08, -0.594568789, 6.75715199e-08, -0.804044724)

         CFrameMon = CFrame.new(932.788818, 6.4503746, 4488.24609, -0.998625934, 3.08948351e-08, 0.0524050146, 2.79967303e-08, 1, -5.60361286e-08, -0.0524050146, -5.44919629e-08, -0.998625934)

      elseif MyLevel == 75 or MyLevel <= 89 then -- Desert Officre

         Ms = "Desert Officer [Lv. 70]"

         QuestName = "DesertQuest"

         LevelQuest = 2

         NameMon = "Desert Officer"

         CFrameQuest = CFrame.new(897.031128, 6.43846416, 4388.97168, -0.804044724, 3.68233266e-08, 0.594568789, 6.97835176e-08, 1, 3.24365246e-08, -0.594568789, 6.75715199e-08, -0.804044724)

         CFrameMon = CFrame.new(1580.03198, 4.61375761, 4366.86426, 0.135744005, -6.44280718e-08, -0.990743816, 4.35738308e-08, 1, -5.90598574e-08, 0.990743816, -3.51534837e-08, 0.135744005)

      elseif MyLevel == 90 or MyLevel <= 99 then -- Snow Bandits

         Ms = "Snow Bandit [Lv. 90]"

         QuestName = "SnowQuest"

         LevelQuest = 1

         NameMon = "Snow Bandits"

         CFrameQuest = CFrame.new(1384.14001, 87.272789, -1297.06482, 0.348555952, -2.53947841e-09, -0.937287986, 1.49860568e-08, 1, 2.86358204e-09, 0.937287986, -1.50443711e-08, 0.348555952)

         CFrameMon = CFrame.new(1370.24316, 102.403511, -1411.52905, 0.980274439, -1.12995728e-08, 0.197641045, -9.57343449e-09, 1, 1.04655214e-07, -0.197641045, -1.04482936e-07, 0.980274439)

      elseif MyLevel == 100 or MyLevel <= 119 then -- Snowman

         Ms = "Snowman [Lv. 100]"

         QuestName = "SnowQuest"

         LevelQuest = 2

         NameMon = "Snowman"

         CFrameQuest = CFrame.new(1384.14001, 87.272789, -1297.06482, 0.348555952, -2.53947841e-09, -0.937287986, 1.49860568e-08, 1, 2.86358204e-09, 0.937287986, -1.50443711e-08, 0.348555952)

         CFrameMon = CFrame.new(1370.24316, 102.403511, -1411.52905, 0.980274439, -1.12995728e-08, 0.197641045, -9.57343449e-09, 1, 1.04655214e-07, -0.197641045, -1.04482936e-07, 0.980274439)

      elseif MyLevel == 120 or MyLevel <= 149 then -- Chief Petty Officer

         Ms = "Chief Petty Officer [Lv. 120]"

         QuestName = "MarineQuest2"

         LevelQuest = 1

         NameMon = "Chief Petty Officer"

         CFrameQuest = CFrame.new(-5035.0835, 28.6520386, 4325.29443, 0.0243340395, -7.08064647e-08, 0.999703884, -6.36926814e-08, 1, 7.23777944e-08, -0.999703884, -6.54350671e-08, 0.0243340395)

         CFrameMon = CFrame.new(-4882.8623, 22.6520386, 4255.53516, 0.273695946, -5.40380647e-08, -0.96181643, 4.37720793e-08, 1, -4.37274998e-08, 0.96181643, -3.01326679e-08, 0.273695946)

      elseif MyLevel == 150 or MyLevel <= 174 then -- Sky Bandit

         Ms = "Sky Bandit [Lv. 150]"

         QuestName = "SkyQuest"

         LevelQuest = 1

         NameMon = "Sky Bandit"

         CFrameQuest = CFrame.new(-4841.83447, 717.669617, -2623.96436, -0.875942111, 5.59710216e-08, -0.482416272, 3.04023082e-08, 1, 6.08195947e-08, 0.482416272, 3.86078725e-08, -0.875942111)

         CFrameMon = CFrame.new(-4970.74219, 294.544342, -2890.11353, -0.994874597, -8.61311236e-08, -0.101116329, -9.10836206e-08, 1, 4.43614923e-08, 0.101116329, 5.33441664e-08, -0.994874597)

      elseif MyLevel == 175 or MyLevel <= 224 then -- Dark Master

         Ms = "Dark Master [Lv. 175]"

         QuestName = "SkyQuest"

         LevelQuest = 2

         NameMon = "Dark Master"

         CFrameQuest = CFrame.new(-4841.83447, 717.669617, -2623.96436, -0.875942111, 5.59710216e-08, -0.482416272, 3.04023082e-08, 1, 6.08195947e-08, 0.482416272, 3.86078725e-08, -0.875942111)

         CFrameMon = CFrame.new(-5220.58594, 430.693298, -2278.17456, -0.925375521, 1.12086873e-08, 0.379051805, -1.05115507e-08, 1, -5.52320891e-08, -0.379051805, -5.50948407e-08, -0.925375521)

      elseif MyLevel == 225 or MyLevel <= 274 then -- Toga Warrior

         Ms = "Toga Warrior [Lv. 225]"

         QuestName = "ColosseumQuest"

         LevelQuest = 1

         NameMon = "Toga Warrior"

         CFrameQuest = CFrame.new(-1576.11743, 7.38933945, -2983.30762, 0.576966345, 1.22114863e-09, 0.816767931, -3.58496594e-10, 1, -1.24185606e-09, -0.816767931, 4.2370063e-10, 0.576966345)

         CFrameMon = CFrame.new(-1779.97583, 44.6077499, -2736.35474, 0.984437346, 4.10396339e-08, 0.175734788, -3.62286876e-08, 1, -3.05844168e-08, -0.175734788, 2.3741821e-08, 0.984437346)

      elseif MyLevel == 275 or MyLevel <= 299 then -- Gladiato

         Ms = "Gladiator [Lv. 275]"

         QuestName = "ColosseumQuest"

         LevelQuest = 2

         NameMon = "Gladiato"

         CFrameQuest = CFrame.new(-1576.11743, 7.38933945, -2983.30762, 0.576966345, 1.22114863e-09, 0.816767931, -3.58496594e-10, 1, -1.24185606e-09, -0.816767931, 4.2370063e-10, 0.576966345)

         CFrameMon = CFrame.new(-1274.75903, 58.1895943, -3188.16309, 0.464524001, 6.21005611e-08, 0.885560572, -4.80449414e-09, 1, -6.76054768e-08, -0.885560572, 2.71497012e-08, 0.464524001)

      elseif MyLevel == 300 or MyLevel <= 329 then -- Military Soldier

         Ms = "Military Soldier [Lv. 300]"

         QuestName = "MagmaQuest"

         LevelQuest = 1

         NameMon = "Military Soldier"

         CFrameQuest = CFrame.new(-5316.55859, 12.2370615, 8517.2998, 0.588437557, -1.37880001e-08, -0.808542669, -2.10116209e-08, 1, -3.23446478e-08, 0.808542669, 3.60215964e-08, 0.588437557)

         CFrameMon = CFrame.new(-5363.01123, 41.5056877, 8548.47266, -0.578253984, -3.29503091e-10, 0.815856814, 9.11209668e-08, 1, 6.498761e-08, -0.815856814, 1.11920997e-07, -0.578253984)

      elseif MyLevel == 300 or MyLevel <= 449 then -- Military Spy

         Ms = "Military Spy [Lv. 330]"

         QuestName = "MagmaQuest"

         LevelQuest = 2

         NameMon = "Military Spy"

         CFrameQuest = CFrame.new(-5316.55859, 12.2370615, 8517.2998, 0.588437557, -1.37880001e-08, -0.808542669, -2.10116209e-08, 1, -3.23446478e-08, 0.808542669, 3.60215964e-08, 0.588437557)

         CFrameMon = CFrame.new(-5787.99023, 120.864456, 8762.25293, -0.188358366, -1.84706277e-08, 0.982100308, -1.23782129e-07, 1, -4.93306951e-09, -0.982100308, -1.22495649e-07, -0.188358366)

      elseif MyLevel == 450 or MyLevel <= 474 then -- God's Guards

         Ms = "God's Guard [Lv. 450]"

         QuestName = "SkyExp1Quest"

         LevelQuest = 1

         NameMon = "God's Guards"

         CFrameQuest = CFrame.new(-4721.71436, 845.277161, -1954.20105, -0.999277651, -5.56969759e-09, 0.0380011722, -4.14751478e-09, 1, 3.75035256e-08, -0.0380011722, 3.73188307e-08, -0.999277651)

         CFrameMon = CFrame.new(-4716.95703, 853.089722, -1933.92542, -0.93441087, -6.77488776e-09, -0.356197298, 1.12145182e-08, 1, -4.84390199e-08, 0.356197298, -4.92565206e-08, -0.93441087)

      elseif MyLevel == 475 or MyLevel <= 524 then -- Shandas

         Ms = "Shanda [Lv. 475]"

         QuestName = "SkyExp1Quest"

         LevelQuest = 2

         NameMon = "Shandas"

         CFrameQuest = CFrame.new(-7863.63672, 5545.49316, -379.826324, 0.362120807, -1.98046344e-08, -0.93213129, 4.05822291e-08, 1, -5.48095125e-09, 0.93213129, -3.58431969e-08, 0.362120807)

         CFrameMon = CFrame.new(-7685.12354, 5601.05127, -443.171509, 0.150056243, 1.79768236e-08, -0.988677442, 6.67798661e-09, 1, 1.91962481e-08, 0.988677442, -9.48289181e-09, 0.150056243)

      elseif MyLevel == 525 or MyLevel <= 549 then -- Royal Squad

         Ms = "Royal Squad [Lv. 525]"

         QuestName = "SkyExp2Quest"

         LevelQuest = 1

         NameMon = "Royal Squad"

         CFrameQuest = CFrame.new(-7902.66895, 5635.96387, -1411.71802, 0.0504222959, 2.5710392e-08, 0.998727977, 1.12541557e-07, 1, -3.14249675e-08, -0.998727977, 1.13982921e-07, 0.0504222959)

         CFrameMon = CFrame.new(-7685.02051, 5606.87842, -1442.729, 0.561947823, 7.69527464e-09, -0.827172697, -4.24974544e-09, 1, 6.41599973e-09, 0.827172697, -9.01838604e-11, 0.561947823)

      elseif MyLevel == 550 or MyLevel <= 624 then -- Royal Soldier

         Ms = "Royal Soldier [Lv. 550]"

         QuestName = "SkyExp2Quest"

         LevelQuest = 2

         NameMon = "Royal Soldier"

         CFrameQuest = CFrame.new(-7902.66895, 5635.96387, -1411.71802, 0.0504222959, 2.5710392e-08, 0.998727977, 1.12541557e-07, 1, -3.14249675e-08, -0.998727977, 1.13982921e-07, 0.0504222959)

         CFrameMon = CFrame.new(-7864.44775, 5661.94092, -1708.22351, 0.998389959, 2.28686137e-09, -0.0567218624, 1.99431383e-09, 1, 7.54200258e-08, 0.0567218624, -7.54117195e-08, 0.998389959)

      elseif MyLevel == 625 or MyLevel <= 649 then -- Galley Pirate

         Ms = "Galley Pirate [Lv. 625]"

         QuestName = "FountainQuest"

         LevelQuest = 1

         NameMon = "Galley Pirate"

         CFrameQuest = CFrame.new(5254.60156, 38.5011406, 4049.69678, -0.0504891425, -3.62066501e-08, -0.998724639, -9.87921389e-09, 1, -3.57534553e-08, 0.998724639, 8.06145284e-09, -0.0504891425)

         CFrameMon = CFrame.new(5595.06982, 41.5013695, 3961.47095, -0.992138803, -2.11610267e-08, -0.125142589, -1.34249509e-08, 1, -6.26613996e-08, 0.125142589, -6.04887518e-08, -0.992138803)

      elseif MyLevel >= 650 then -- Galley Captain

         Ms = "Galley Captain [Lv. 650]"

         QuestName = "FountainQuest"

         LevelQuest = 2

         NameMon = "Galley Captain"

         CFrameQuest = CFrame.new(5254.60156, 38.5011406, 4049.69678, -0.0504891425, -3.62066501e-08, -0.998724639, -9.87921389e-09, 1, -3.57534553e-08, 0.998724639, 8.06145284e-09, -0.0504891425)

         CFrameMon = CFrame.new(5658.5752, 38.5361786, 4928.93506, -0.996873081, 2.12391046e-06, -0.0790185928, 2.16989656e-06, 1, -4.96097414e-07, 0.0790185928, -6.66008248e-07, -0.996873081)

      end

   end

   if Sea2 then

      if MyLevel == 700 or MyLevel <= 724 then -- Raider [Lv. 700]

         Ms = "Raider [Lv. 700]"

         QuestName = "Area1Quest"

         LevelQuest = 1

         NameMon = "Raider"

         CFrameQuest = CFrame.new(-424.080078, 73.0055847, 1836.91589, 0.253544956, -1.42165932e-08, 0.967323601, -6.00147771e-08, 1, 3.04272909e-08, -0.967323601, -6.5768397e-08, 0.253544956)

         CFrameMon = CFrame.new(-737.026123, 39.1748352, 2392.57959, 0.272128761, 0, -0.962260842, -0, 1, -0, 0.962260842, 0, 0.272128761)

      elseif MyLevel == 725 or MyLevel <= 774 then -- Mercenary [Lv. 725]

         Ms = "Mercenary [Lv. 725]"

         QuestName = "Area1Quest"

         LevelQuest = 2

         NameMon = "Mercenary"

         CFrameQuest = CFrame.new(-424.080078, 73.0055847, 1836.91589, 0.253544956, -1.42165932e-08, 0.967323601, -6.00147771e-08, 1, 3.04272909e-08, -0.967323601, -6.5768397e-08, 0.253544956)

         CFrameMon = CFrame.new(-973.731995, 95.8733215, 1836.46936, 0.999135971, 2.02326991e-08, -0.0415605344, -1.90767793e-08, 1, 2.82094952e-08, 0.0415605344, -2.73922804e-08, 0.999135971)

      elseif MyLevel == 775 or MyLevel <= 799 then -- Swan Pirate [Lv. 775]

         Ms = "Swan Pirate [Lv. 775]"

         QuestName = "Area2Quest"

         LevelQuest = 1

         NameMon = "Swan Pirate"

         CFrameQuest = CFrame.new(632.698608, 73.1055908, 918.666321, -0.0319722369, 8.96074881e-10, -0.999488771, 1.36326533e-10, 1, 8.92172336e-10, 0.999488771, -1.07732087e-10, -0.0319722369)

         CFrameMon = CFrame.new(970.369446, 142.653198, 1217.3667, 0.162079468, -4.85452638e-08, -0.986777723, 1.03357589e-08, 1, -4.74980872e-08, 0.986777723, -2.50063148e-09, 0.162079468)

      elseif MyLevel == 800 or MyLevel <= 874 then -- Factory Staff [Lv. 800]

         Ms = "Factory Staff [Lv. 800]"

         QuestName = "Area2Quest"

         LevelQuest = 2

         NameMon = "Factory Staff"

         CFrameQuest = CFrame.new(632.698608, 73.1055908, 918.666321, -0.0319722369, 8.96074881e-10, -0.999488771, 1.36326533e-10, 1, 8.92172336e-10, 0.999488771, -1.07732087e-10, -0.0319722369)

         CFrameMon = CFrame.new(296.786499, 72.9948196, -57.1298141, -0.876037002, -5.32364979e-08, 0.482243896, -3.87658332e-08, 1, 3.99718729e-08, -0.482243896, 1.63222538e-08, -0.876037002)

      elseif MyLevel == 875 or MyLevel <= 899 then -- Marine Lieutenant [Lv. 875]

         Ms = "Marine Lieutenant [Lv. 875]"

         QuestName = "MarineQuest3"

         LevelQuest = 1

         NameMon = "Marine Lieutenant"

         CFrameQuest = CFrame.new(-2442.65015, 73.0511475, -3219.11523, -0.873540044, 4.2329841e-08, -0.486752301, 5.64383384e-08, 1, -1.43220786e-08, 0.486752301, -3.99823996e-08, -0.873540044)

         CFrameMon = CFrame.new(-2913.26367, 73.0011826, -2971.64282, 0.910507619, 0, 0.413492233, 0, 1.00000012, 0, -0.413492233, 0, 0.910507619)

      elseif MyLevel == 900 or MyLevel <= 949 then -- Marine Captain [Lv. 900]

         Ms = "Marine Captain [Lv. 900]"

         QuestName = "MarineQuest3"

         LevelQuest = 2

         NameMon = "Marine Captain"

         CFrameQuest = CFrame.new(-2442.65015, 73.0511475, -3219.11523, -0.873540044, 4.2329841e-08, -0.486752301, 5.64383384e-08, 1, -1.43220786e-08, 0.486752301, -3.99823996e-08, -0.873540044)

         CFrameMon = CFrame.new(-1868.67688, 73.0011826, -3321.66333, -0.971402287, 1.06502087e-08, 0.237439692, 3.68856199e-08, 1, 1.06050372e-07, -0.237439692, 1.11775684e-07, -0.971402287)

      elseif MyLevel == 950 or MyLevel <= 974 then -- Zombie [Lv. 950]

         Ms = "Zombie [Lv. 950]"

         QuestName = "ZombieQuest"

         LevelQuest = 1

         NameMon = "Zombie"

         CFrameQuest = CFrame.new(-5492.79395, 48.5151672, -793.710571, 0.321800292, -6.24695815e-08, 0.946807742, 4.05616092e-08, 1, 5.21931227e-08, -0.946807742, 2.16082796e-08, 0.321800292)

         CFrameMon = CFrame.new(-5634.83838
