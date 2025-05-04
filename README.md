# Chat-X
The Android version of the instant messaging package contains: text, files, pictures, videos, music and other data real-time communication (based on socket.io creation), thanks to the cross-platform convenience 🍺🍺 brought by the socket.io (more : Larger files are divided into fragment transfers)

# Usage

chat.x.connect("https://your-socket-server.com", userId)

chat.x.sendTextMessage(receiverId: String, content: String)

chat.x.sendImageMessage(friendId, imageUri)
