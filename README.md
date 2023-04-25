#Skup-projekt-Hodnocení

import sys
from PyQt5.QtWidgets import QApplication, QWidget, QPushButton


from PyQt5.QtGui import QIcon
from PyQt5.QtCore import pyqtSlot


class App(QWidget):

    def __init__(self):
        super().__init__()
        self.title = 'hodnocení'
        self.left = 20
