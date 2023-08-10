# Face Changing Program

This program helps you choose the faces you want to change in a group image and change them with the faces you want to with a pretrained model using the library insightface.

# Repo Setup

Create 2 folders in home directory:
middleware
frames

Install : https://cdn-lfs.huggingface.co/repos/f7/42/f7423c2763d9e027230d619d2842edc5fcb860ccd6c5e49b20aea08bce8851b5/e4a3f08c753cb72d04e10aa0f7dbe3deebbf39567d4ead6dce08e98aa49e16af?response-content-disposition=attachment%3B+filename*%3DUTF-8%27%27inswapper_128.onnx%3B+filename%3D%22inswapper_128.onnx%22%3B&Expires=1691443676&Policy=eyJTdGF0ZW1lbnQiOlt7IkNvbmRpdGlvbiI6eyJEYXRlTGVzc1RoYW4iOnsiQVdTOkVwb2NoVGltZSI6MTY5MTQ0MzY3Nn19LCJSZXNvdXJjZSI6Imh0dHBzOi8vY2RuLWxmcy5odWdnaW5nZmFjZS5jby9yZXBvcy9mNy80Mi9mNzQyM2MyNzYzZDllMDI3MjMwZDYxOWQyODQyZWRjNWZjYjg2MGNjZDZjNWU0OWIyMGFlYTA4YmNlODg1MWI1L2U0YTNmMDhjNzUzY2I3MmQwNGUxMGFhMGY3ZGJlM2RlZWJiZjM5NTY3ZDRlYWQ2ZGNlMDhlOThhYTQ5ZTE2YWY%7EcmVzcG9uc2UtY29udGVudC1kaXNwb3NpdGlvbj0qIn1dfQ__&Signature=DCeTJa%7E4VJdD96fXygnc7pW7TsKlaXuBdRM0ltVF0U%7E2S4tSTON6ANm-PK%7EM3ltZBhPjEYlp%7EF7SANHthRXK7zUfaOMQkDvth3GgypgPl0Em3XqGMZ5fCF2EHv8VnyXq0TB67WhvYflD8ELfk01fdfVFkUusmhqbCaGJNhRwCaojRGQHj%7EU7nXxs39YxVR8AVLl-vJ%7EEBZk4EkCm9bUk3mGZy0F8dVkzha42mGynuTiyQVqQTZPg1MLz5mvHyysaWsCsrjDjtnRMNiw73PIERtgdB7INM5jilT4TikQ3miSW%7Es538PFi8-oUOCWMoANcoiUtzajcJ1zZ2cXjvtAPLg__&Key-Pair-Id=KVTP0A1DKRTAX

Save the above file in the repo directory with the name inswapper_128.onnx

# Execution

```
pip install -r requirements.txt
python demo01.py
python demo01.py
```

The images in the demo.py file can be changed. The first parameter is the group picutre and the second parameter is array of faces that you want to use in order to replace.
