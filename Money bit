Client = discord.Client()
client = commands.Bot(command_prefix = "!")
conn = sqlite3.connect('galactic_credit_standard_bank.db')
c = conn.cursor()

def create_table():
    c.execute('CREATE TABLE IF NOT EXISTS GalacticBank(user REAL, money INT)')
def dynamic_data_entry():
    user = 'userID'
    money = '0'
