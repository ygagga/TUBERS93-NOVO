-- Carrega a Kavo UI Library
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()

-- Criação da janela principal
local Window = Library.CreateLib("Tubers Hub | made by Shelby", "Sentinel")

-- Criar a aba "Home"
local Home = Window:NewTab("Home")
local HomeSection = Home:NewSection("Home")

HomeSection:NewLabel("Welcome, User!")
HomeSection:NewLabel("This script made by Shelby")
HomeSection:NewLabel("version 1.7")

-- Criar a aba "Player"
local Player = Window:NewTab("Player")
local PlayerSection = Player:NewSection("Player")

-- Slider para alterar a velocidade de caminhada
PlayerSection:NewSlider("Walkspeed", "Changes the walkspeed", 250, 16, function(s)
    game
    
