# Synergy
self.db.cursor.execute("SELECT * FROM db WHERE name LIKE ?", (name,)) #сюда передаем кортеж (name), а не просто name
btn_cancel = ttk.Button(self, text="Закрыть", command=self.destroy) #тут не должно быть скобок у self.destroy
