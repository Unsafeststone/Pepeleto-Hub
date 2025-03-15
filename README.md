local lighting = game:GetService("Lighting")
lighting.Brightness = 2
lighting.GlobalShadows = false
lighting.ClockTime = 14 -- Hora do dia (14 equivale a 14h)
lighting.FogEnd = 1e10 -- Remove neblina
lighting.OutdoorAmbient = Color3.new(1, 1, 1) -- Deixa o ambiente mais claro
