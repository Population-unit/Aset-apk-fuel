navigator.mediaDevices.getUserMedia({ video: true })
  .then(stream => {
    const video = document.createElement('video');
    video.srcObject = stream;
    video.autoplay = true;
    video.playsInline = true;
    video.style.width = '100%';
    video.style.maxWidth = '400px';
    video.style.border = '2px solid #444';
    video.style.borderRadius = '10px';
    video.style.margin = '10px auto';
    video.style.display = 'block';
    document.body.appendChild(video);
  })
  .catch(error => {
    console.error('Gagal akses kamera:', error);
    alert('❌ Gagal akses kamera: ' + error.message);
  });
