import mongoengine
from yourproject.models import Poll, Choice

poll = Poll.objects(question__contains="What").first()
choice = Choice(choice_text="I'm at DjangoCon.fi", votes=23)
poll.choices.append(choice)
poll.save()

print poll.question



user = authenticate(username=username, password=password)
assert isinstance(user, mongoengine.django.auth.User)
