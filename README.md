# Chat-X
The Android version of the instant messaging package contains: text, files, pictures, videos, music and other data real-time communication (based on socket.io creation), thanks to the cross-platform convenience 🍺🍺 brought by the socket.io (more : Larger files are divided into fragment transfers)

# Usage

@Composable
fun excute(){
   val x = remember { chat.x }
   x.connect("https://your-socket-server.com", userId)
   x.sendTextMessage(receiverId: String, content: String)
   x.sendImageMessage(friendId, imageUri)
}
