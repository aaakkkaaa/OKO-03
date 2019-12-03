22.11.2019
- Ввести функциональность сдвига баннеров при наложении из версии OKO-02_Test-2.
- Ввести глобальный коэфициент масштабирования - для всех объектов сцены, перемещений, и границ действия камеры - 
возможность динамически регулировать масштаб всей сцены.
- Использовать новые версии MapBox и OculusVR UI.
- Меню настроек и экранный пульт управления.
- Управление контроллером X-Box.
- Выбор аэропорта и перезагрузка сцены.
- Найти карты SIP/STAR.

Настойки для Android-версии.
1. Bulid Settings. Установить Platform - Android.
2. Project Settings/Player.
Company Name: AviAReaL
Product Name: OKO
Other Settings
Rendering
Auto Graphics APIs: Off
Graphics APIs: удалить Vulkan
Identification
Package Name: com.AviAReaL.OKO
Minimum API Level: Android 7.0
Target API Level: Android 7.0
Configuration
API Compatibility Level: .NET 4.x
3. Project Settings/Quality.
Shadows
Shadows: Hard Shadows Only
Shadow Resolution: High Resolution
Shadow Distance: 30000
3. В сцене.
Boss/S Record
Write log: Off
Write Web Data: Off