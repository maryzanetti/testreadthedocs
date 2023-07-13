Resseguro
=====

.. _descriçao:

Descrição
------------

Resseguro é a operação pela qual o segurador transfere a outro, total ou parcialmente, um risco assumido através da emissão de uma apólice ou um conjunto delas. Dessa forma reduz-se a responsabilidade na aceitação de um risco considerado excessivo, cedendo a outro uma parte da responsabilidade e do prêmio recebido.
Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

