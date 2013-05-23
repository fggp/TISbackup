# -----------------------------------------------------------------------
#    This file is part of TISBackup
#
#    TISBackup is free software: you can redistribute it and/or modify
#    it under the terms of the GNU General Public License as published by
#    the Free Software Foundation, either version 3 of the License, or
#    (at your option) any later version.
#
#    TISBackup is distributed in the hope that it will be useful,
#    but WITHOUT ANY WARRANTY; without even the implied warranty of
#    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
#    GNU General Public License for more details.
#
#    You should have received a copy of the GNU General Public License
#    along with TISBackup.  If not, see <http://www.gnu.org/licenses/>.
#
# -----------------------------------------------------------------------


Le script tisbackup se base sur un fichier de configuration .ini. Cf le fichier d'exemple pour le format

Pour lancer le backup, lancer la commande
./tisbackup.py -c fichierconf.ini 

Pour lancer une section particulière du fichier .ini
./tisbackup.py -c fichierconf.ini -s section_choisi

Pour mettre le mode debug
./tisbackup.py -c fichierconf.ini -l debug 
