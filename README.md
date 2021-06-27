# What is this?

Some guy asked following question on slack;

---

Hi all,  I’ve got what has got to be the most basic symfony question.  I’ve used Symfony as part of Drupal, but this is my first time to mess with it directly.  I’m trying to get it going on an existing project and I can not get it to recognize my route for the life of me.
Here is my controller:

```
final class IndexController extends AbstractController
{
    /**
     * @Route("/", methods={"GET"})
     * @return Response
     */
    public function indexAction(): Response
    {
        return $this->render('index.html.twig');
    }
}
```
I’ve been banging my head against this for a couple of hours now, and I’m sure it is something silly.

---

So in this repository I'm trying to show how to solve this issue.

## License

[The MIT License (MIT)](LICENSE)

Copyright © 2021 Tarmo Leppänen
