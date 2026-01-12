21927948-cfe2-4f13-91fa-ccd433291b79curl https://api.x.ai/v1/chat/completions \
    -H "Content-Type: application/json" \
    -H "Authorization: Bearer xai-nt0VPdJaWHKsjHQCgXdm2qyEDPzzdHZMXEwqo855HkC3AR6x8ZPzMimF0rFLZc33lBg67ziMvwUeUiY7" \
    -d '{
      "messages": [
        {
          "role": "system",
          "content": "You are a test assistant."
        },
        {
          "role": "user",
          "content": "Testing. Just say hi and hello world and nothing else."
        }
      ],
      "model": "grok-4-latest",
      "stream": false,
      "temperature": 0
    }'xai-nt0VPdJaWHKsjHQCgXdm2qyEDPzzdHZMXEwqo855HkC3AR6x8ZPzMimF0rFLZc33lBg67ziMvwUeUiYx-ai/grok-4.1-fast
