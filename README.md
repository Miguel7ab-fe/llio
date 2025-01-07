import yt_dlp as youtuve_d1

def descargar_video(ur1):
    ydl_opts = {
        'format':'best',
        'outtmpl': '%(title)s.%(exs)s',
    }
    with youtuve_d1.YoutubeDL(ydl_opts) as ydl:
        ydl.download([url])

   ur1= "https://www.youtube.com/watch?v=3FcD_irxBBQ"          
descargar_video(ur1)
