DISCORD SINGS BOT.PY for discord.py 2.0
Orignal by Boomerang Rosalina Development; Remade by Sonic the Dev

Ever wanted to do Discord sings events but you are kind of lonely or want a bot to join in? Well this source code is PERFECT for you.
This source code will watch for a list of words or phrases and response with Lyrics that you set in it in the channels that are enabled to sing in.

This source code was orignally from: https://github.com/BoomerangRosalina/DiscordSingsBot.py
This source code has been remade for discord.py 2.0+ as in discord.py 2.0, you need to specify all the intents being used in the bot.
I even added some Sonic Music Lyrics as an example of lyrics the bot can respond too.

================================================

Instructions for Setup
1. Download/Fork this Source code
2. Create a Bot Application in the Developer Portal and create a bot and copy the bot token. Make sure the Message content intent is enabled.
3. At the bottom with client.run("YOURBOTTOKEN"), replace YOURBOTTOKEN with your bot token.
4. On the On Message
>>> responses = [], Add quotations and put in a lyric sample of what a response you want the bot to respond too. (See the example in main.py)
5. At the bottom, you would see singtrigger = []. You can customize this this with phrases you want the bot to sing with.
>>> Example: singtrigger = ["free", "city", "you"]
6. Save Everything and run the bot.

Optional Steps:
At client = commands.Bot(command_prefix='!'), replace ! with the prefix you want.

=================================================

HOW TO USE/HOW DOES IT WORK.

To have a bot sing in a text channel you want, simply do <prefix>singtrue in the channel you want and the bot will store your channel id
and know to sing in that channel if it sees the word(s) or letter(s) that is in singtrigger = ["world", "night"]
To disable the bot from singing in the enabled text channel, use <prefix>singfalse in the enabled channel.
Check the json file for what channel ids are stored in the bot.

=================================================

LICENSE:
You are free to use, distribute, modify this source code however you please under the MIT license.

DISCLAIMER:
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
USE OF THIS SOFTWARE IS AT THE RISK OF THE USER OBTAINING THIS SOFTWARE

===========================================