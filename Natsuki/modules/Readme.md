## 𝐆𝐎 𝐌𝐚𝐬𝐭𝐞𝐫 [ᴀꜱꜱɪꜱᴛᴀɴᴛ] Example plugin format
```python3
from Natsuki.decorator import register
from .utils.disable import disableable_dec
from .utils.message import get_args_str

@register(cmds="GOMaster")
@disableable_dec("GOMaster")
async def _(message):
    j = "Hello there my name is 𝐆𝐎 𝐌𝐚𝐬𝐭𝐞𝐫 [ᴀꜱꜱɪꜱᴛᴀɴᴛ]"
    await message.reply(j)
    

__help__ = """
<b>Hi</b>
- /hi: Hello there my name is 𝐆𝐎 𝐌𝐚𝐬𝐭𝐞𝐫 [ᴀꜱꜱɪꜱᴛᴀɴᴛ]
"""
__mod_name__ = "𝐆𝐎 𝐌𝐚𝐬𝐭𝐞𝐫 [ᴀꜱꜱɪꜱᴛᴀɴᴛ]"
```
