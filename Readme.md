echo "CuUBCscBCngKDRILc351ZWxsby1wb2MSHgoGZHJpdmVyGhRLcnVQeWlGcWNIdGtDOEJRYlZ1bxIpChFpbl9wcm9ncmVzc19yb3V0ZRoUWlF6M0tEekVMT3F4ZFJreDVNQmwSHAoEam9icxoUNlNpcUdTS3lnU3RzbGd2UXA2dmMaDQoCaWQSBxDvkTiYAQEaIQoEZGVwcxIZShcKBxDtkTiYAQEKDIoBBjkxOTc5MJgBARoZCgZzdGF0dXMSD4oBCWJsb2NrZWQxM5gBASoMCJO2urwGEJj66LUDMgsIufvcugYQoMXwDhLlAQrHAQp4Cg0SC3N+dWVsbG8tcG9jEh4KBmRyaXZlchoUS3J1UHlpRnFjSHRrQzhCUWJWdW8SKQoRaW5fcHJvZ3Jlc3Nfcm91dGUaFFpRejNLRHpFTE9xeGRSa3g1TUJsEhwKBGpvYnMaFDZTaXFHU0t5Z1N0c2xndlFwNnZjGg0KAmlkEgcQ75E4mAEBGiEKBGRlcHMSGUoXCgcQ7ZE4mAEBCgyKAQY5MTk3OTCYAQEaGQoGc3RhdHVzEg+KAQlibG9ja2VkMTKYAQEqDAiZsbq8BhCYjbGOAzILCLn73LoGEKDF8A4aCAoGc3RhdHVz" | base64 -d > message.bin

protoc --decode_raw < message.bin
