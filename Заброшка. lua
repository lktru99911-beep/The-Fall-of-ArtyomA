-- THE FALL OF ARTYOM
-- Abandoned Building Stage
-- Psych Engine

function onCreate()
    -- Камера
    setProperty('defaultCamZoom', 0.75)

    -- Небо и дальний фон
    makeLuaSprite('darkSky', '', -600, -300)
    makeGraphic('darkSky', 2500, 1400, '08090D')
    setScrollFactor('darkSky', 0.3, 0.3)
    addLuaSprite('darkSky', false)

    -- Задняя стена
    makeLuaSprite('backWall', '', -500, -200)
    makeGraphic('backWall', 2300, 1100, '242329')
    setScrollFactor('backWall', 0.8, 0.8)
    addLuaSprite('backWall', false)

    -- Тёмные окна
    makeLuaSprite('window1', '', -100, 40)
    makeGraphic('window1', 210, 280, '090D16')
    addLuaSprite('window1', false)

    makeLuaSprite('window2', '', 650, 20)
    makeGraphic('window2', 230, 300, '090D16')
    addLuaSprite('window2', false)

    -- Рамы окон
    makeLuaSprite('frame1', '', -110, 165)
    makeGraphic('frame1', 230, 12, '55505A')
    addLuaSprite('frame1', false)

    makeLuaSprite('frame2', '', 755, 20)
    makeGraphic('frame2', 12, 300, '55505A')
    addLuaSprite('frame2', false)

    -- Разбитые участки стены
    makeLuaSprite('crack1', '', 250, 100)
    makeGraphic('crack1', 170, 8, '111116')
    setProperty('crack1.angle', -25)
    addLuaSprite('crack1', false)

    makeLuaSprite('crack2', '', 420, 220)
    makeGraphic('crack2', 120, 7, '111116')
    setProperty('crack2.angle', 18)
    addLuaSprite('crack2', false)

    -- Пол
    makeLuaSprite('floor', '', -600, 570)
    makeGraphic('floor', 2500, 500, '171619')
    setScrollFactor('floor', 1, 1)
    addLuaSprite('floor', false)

    -- Трещины на полу
    makeLuaSprite('floorCrack1', '', 100, 640)
    makeGraphic('floorCrack1', 230, 6, '55505A')
    setProperty('floorCrack1.angle', -12)
    addLuaSprite('floorCrack1', false)

    makeLuaSprite('floorCrack2', '', 700, 610)
    makeGraphic('floorCrack2', 180, 5, '55505A')
    setProperty('floorCrack2.angle', 15)
    addLuaSprite('floorCrack2', false)

    -- Обломки и мусор
    makeLuaSprite('debris1', '', 40, 550)
    makeGraphic('debris1', 100, 25, '39343A')
    setProperty('debris1.angle', 12)
    addLuaSprite('debris1', false)

    makeLuaSprite('debris2', '', 800, 545)
    makeGraphic('debris2', 130, 30, '302C32')
    setProperty('debris2.angle', -8)
    addLuaSprite('debris2', false)

    -- Тёмная передняя тень
    makeLuaSprite('darkness', '', -600, -300)
    makeGraphic('darkness', 2500, 1400, '08080D')
    setProperty('darkness.alpha', 0.20)
    setScrollFactor('darkness', 1, 1)
    addLuaSprite('darkness', true)
end
