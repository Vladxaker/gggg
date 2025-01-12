import kivy
from kivy.app import App
from kivy.uix.label import Label
from kivy.core.window import Window

kivy.require('2.0.0')  # Укажите требуемую версию Kivy

class HelloApp(App):
    def build(self):
        Window.clearcolor = (1, 1, 1, 1)  # Белый фон
        return Label(text='Привет', font_size=50, color=(0, 0, 0, 1))  # Черный текст

if __name__ == '__main__':
    HelloApp().run()
