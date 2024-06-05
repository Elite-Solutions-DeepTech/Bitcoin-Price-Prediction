# Bitcoin price prediction using machine learning
This presentation provides an in-depth analysis of Bitcoin's price history, key factors influencing its value, and techniques for making short-term and long-term price predictions. The goal is to equip the audience with a comprehensive understanding of the cryptocurrency market and strategies for navigating its volatility.![enter image description here](data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBxMQEhUSEhIVFhUVFxUVFRUVEhUVFRUVFRIWFhYVFRUYHSggGBolHRUVITEhJSkrLi4uFx8zODMtNygtLi0BCgoKDg0OGxAQGy0mICUtLS0tLS0tLS0tLi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLf/AABEIAKMBNgMBEQACEQEDEQH/xAAbAAACAwEBAQAAAAAAAAAAAAACAwEEBQYAB//EAEIQAAIBAgQCCAMFBgUDBQEAAAECEQADBBIhMQVBBhMiUWFxgZEyobEjQlJywRRikrLR8AczQ4Kic8LhFVNj0vEk/8QAGgEAAwEBAQEAAAAAAAAAAAAAAQIDBAAFBv/EADgRAAEDAgMECQMEAgEFAAAAAAEAAhEDIQQSMUFRcfATImGBkaGxwdEFMuEUI0LxM1IGFVNicpL/2gAMAwEAAhEDEQA/APiIrYEqmigpAoLlNCUFNBBSKC5TXIKYoILwFcuRAUEEUUsoKYrkJUxQlCUUUAbISpiumyErwFdK6VMV0oSiy0JC6VGWjK6V4iuBXAogulCboSvBaJIXSvZa6V0owmmxpc10ua6lbZ8K4uQLk0W9d/lSykzK3hrY8TSOJUKjiu66CdHExj5WYIAJ7yddhWd74N1gyvr1hSDonavqvDeh+Fsx2M5HN9fltUTWOxetR+jUG3fLj26eC22tqinKAAAdAIFKHFzhK3vp06VI5QAI2L4Rxy9mLeNxj71twz+sV8VhheexVXb7T/Yn8te1RNlUDqd5VhblaQVItU4i5pb/ADt/LXE6IU23dwCLraaUuRBi7n2Dfnt/WuceqnpN/eHApDXq6VQMXsNe+0T8w+tcDddUZ1HcFjNd7T/nf+Y1GblegG9VvAei4cVjC+lUiuQU0EFNBciAoSlUgUJQUxQlciihKC8BXIIgKCCICggiApZshK9FdKEoitK02QlEFoTZCVMUZQUxQldKkJQLghK9k8q7MulEU8a4HsQlSFEV15QkyvAeFHvXKda6yFkYUwaBiUJErypRlcSmZNaEpJsruEt/SpOKz1XLsOjC3AyZJzTpG8zWd1yvFxTiX9XXZxX27D3iiILzAOYB7i0bCoEXsvr6VboaTBiHAONu9e4rcy2bjdyn6U1MdZd9Rflwrz2L4HxG5uf3j9KvhLlfKUG6cEnE3PtB+S3/AC171LRUpt/b7yjFytAKUtXsTd7Nv87fy1xOi6m3rO4Be62mldkQ4q79g/57f1oOPVRps/ebwKqteoSrBijDXvtE/MPrRBujUZ1DwWZcudp/zt/MalNytgb1W8AuSFZl7qIVyCmlQUxQQRRSlBEBQJQUxQ2oIooSgvAV03XIgKWbIIgKWbpUYWlzWQlEFoZroSiy0oJhLKKK68ISpA8KMbyhKKKFkJXstGV0r2WjK6VJWgEJRBNNqE3QzXRLbNEuCBcEfVeNDMlzq7ZwE2XfXsso96QvOZZn4iKrWbwVWW2O7500lWLinhNdhSzZTzWWvwzDk+1ScVgxFQAL6z0F4GLSftN3TQlJ5Dm1Re6LBafpeFbfF1dBp8/Cw+l3SbPc0MAfCO4d/nU3HKIC8vFVn4+qXn7R9o9+9De6du+Fa2QC2WCx3g6e9M0OIkLS7FYl1L9O+437Y3flcFib2ZZ/e/StmFZlKemyHR2IcU/2g/6dv6V7FM2TU29Q8SvdZVgUMqHE3ezb/O38tcTompt6zuAQm9RlHIov3vsX/Mn1rnHqosZ+83gVVa7QlWDFFi721/MPrXA3Re3qHgqNx+035m+tJNytDW9UcAucAqK9dGBSkpUQFLKEoqCCIClQRAUClUxQm66VMUs2QXgK4zKBTAKQ6FKjApbShKILXTZLKILpQJMoSmZPCkDrapMyMW9dqGcQlzWXglGbrpRZNqEoSpyb0ZK7Moy+FFdKMrQCWUy3b0oTdK511vYPgyvhzcIOYZjI5xECpueZXmVca5tfJsss6zhZMU+ay1OqwF2drgJTDHMjDN1LGQRMsQSKhmleRUq1Olzm0THBYfFeDhGuFdAjhQPMCnzLVh8USGtdqQVRt4Uljod6Oayu6qA1d70F6OG+8sOwsFvH92pudAlRwuGOMrZf4jX4XQ9OekC216lDoNGjvH3fIVMCLlW+q4vpn/paP2t1+O5fI8Xjc9znv30zaZcUKVHIxDav9htBsN5POtzKcJnM64uoe+RaBEDtnYD8NXa0BcKYNS+73S8fcm4D/wDHb+la2aJqLYpkdpQdZVJT5UGJudlPzH6VxOiam3rO4IC9GUcqi9c+yf8AMn1ribIsb+6OBVcvXSqhq9ZftL5j61wN1zh1Sqtxu035j9aU6q7R1RwWGtSXolGKVBFFKlRgUqVGBS2hBEBSkhKvRXTdcpilnqoSiApSboEpgWpzYpZRha4EyllMVfCl2apCUxF0oGJSk3WhgeHNeYqDspb2FQzhrdFlq4gUwCd6S+HymDTtfIsnFSRISgulU2p5RhNRSzYoSrFnBs0wDuOVTdWa3aq06ZctXCdHmdGMGQVj1OtZXY5odYrSMK6QFLdG7p0CnbkpNBv1BhsmdgHxKv8ADOiGIZlBs3ILLJKMBE6kmNqp05cbAry8TQrts1srt7vRG5bw6rbZZDOzr+5OwJ32FEPO1Yav0ytk6Q3deRwWHY6I3jluqkq5cjvgE8qOfYo9FiHUg4NkHTuX0+5dtBURysstsKpiTqNhUwDsXuvqUA1rKhEkNgHiua6Y8CDJiLykCGt9kDeAAfr8qcO2LzPqGDDX1MQNAQI4gLi+E8He9eFtQZJ9hzJqq85maqQymLlfSuJYhOHYYWrcBo35+LmpfcZXt4ys36dhxQpfe7kn4XxrpDxIufi7+fjVAJXm4LD5blY+EUFhLfKtdNkLdVJy2CdaKBW+I6DuHMVoCRwdmGiG5dXqh2T8Z3b93wFOEWtd0muz3Ssc8uOXYT6VoZonothh4lKz06eEF9uyv5j9K4lMwXPBCXoyjCi632bea/WuJsi0fuDvSS1cqQott2h5igDdFw6pVa43abzP1oTdVA6oWUtItxRilSlEKVBGBSpJTAtITZLKMClJQJXo0pSboTdTFL/FBGq0CesgSmqtTJsUhKYF09aWet3JJumLbM7UudoGqQuEJ9qwYpXVGypueJXd9A+BG/cuQQIttv4wBWQ1JCwGm7EksbsBPPikdPOF9TiSAgUFUI00+ET8waal9sSmDXUnGmbaLkSpjT6VotK0zdafDeGPcZYB5VjxGJp02lehhcJnMr6N0e6FgQ945RIInn6V5uapW6x6re3bwXstpMYIAkroz1FkBbSKxMatrzOuVe7U6mkzXikJ7TfyHuVYU9r7KhjeKXoypcKsR8KKiZdoUqJYscw28e6tdCk55hzjw08QElRzQLD3S7yXRJ6y/m1gG7eUkzpADHSIJPLuFekzCU4OZvr8rDUqOkQefD+lm3eM4i04XrX5SC6surhP9UF43adNPI0f0zNgjxU+mcNvpw49vBXuG9LLhOU28xWJFsBGGdc0ZCSJiZkrqNKDqD288+iAe07PC2vYgfDJiCLtm8QyjRXmVnUeKju3HjFVa5p6pEHyXz+L+kZiX0XeOz4XR8Lw7XLDJek5rizJmR2NiNx5VOqwscq4Ci+phXU8RMl4me5OsYOzghdvxEn2/dHmaSSbLSyjh/p7alfw+BxK+V9L+PG6zknf5eA8KcDYvBpB+IqmtU1Pl2LhLzFzsedaKbV7TAGhWcJYaRoa0NUar2wbryWjlbYaDdh3iqhcXDMEFy39n8S/H3/u04N0zXfuaHRJxp7Y1nsJt5VZuiekOp3lKzUypCG82i/mP0riiwXPBCWoymhDdbsN5rXTZc0dcd6UWrpVIUI2o864ariLFIc6nzNBVAsFnrSFaijFJtSoxQQTBSXSIwKQzCVMUUjibJCVJXSlJMrpupC60pJyoTZOtJ4VNxObVTc5bXCuCvfPZAA2k98TWZ1QCxWDEYxlLXVTguGtcbJtvr5A0hqAGwS1cS1jcyi/w57bQw5TvyIpw9sIsxDHiWqzwvhxusqiJZgB5mue9JVqwYC+xdE+jxwLtnI7SlZnskgggD51mmVqwmHfh6pNTaCPRZ3+JmCLlSIkd/cEJpln+qdXEB3YuSxXR8uZUazbWBtrbB96nUqZATC76Uw1HQ5dfwrAW8HlUgNe0B0lbZiQD3v+7715Lw6cxud2wfJ7NF9pRoQy1gtl8zKzm4Ai6MzTBI+IaeogbedUdTc6S827fwqCBAaLrPxuLQKOotZmJnNdzKp1kjJMnloeUa1ppgDRvFAgnUqniuK4m46stzKEmFtIkidO2r6mI5RWtptclSLAqb8QxAu9aL98vlyR1ACgTO0ATPM1VrWAQB5qbglWeK3Bcu3LuS8HCKVuIhW2F3+0C6E6dnXbTeqguAAaVkfSB1AKrYFbbZ7l1+ouhnCJo1oWyATGmkgCR8Qyz3VXpQ0AG/as/RumQe7UKhYuuGVkZ1mchuKyGQxa7dEgZ2cnYbA6jQA6KjARcc+3PdBkk3t5d/bw8l1fAulOuUkMJG2geAGleQeCDEwQZ74iIAyvuPMLnEg832qj024w5kqT1bar3AxB9dD86JwrmiRpvXgY5tWrX656kyBsXzDHYpnnX+5pW0wDdbaNJrYSbdpiBAY77A99aGgKjnNBOitWcJckdhv4TVAovq04+4IUwFzK0rGg3ZRzHeaoETXp5hf1S7mDYJBZB2v/AHF7vCmGqZtZueQDpuKqY7R4kHsJqDI2qrdFejdk9pSc1MqQhvNovmfpXIsFzwQlqKaENxuwfMfWgUWjrBKLUU8LyHUedcuIskOdT5mgqAWCprSlaSmLSHVIUwUlpSFMApLJUxRrUzGVISmqKm7ZdISpK6UpPWQm6JV1pSeqECbLQwVqeVZ6h6yy1XQvsfQHo7bfDdYxYNnO3gsfrWWTKzYbAU8W01HkyCR5KrwHoohxVxWJhFzjxnkfeiTtWbD4f9RUNJ5s0Tx0hT/iD0fTN1lsZezEAaQqTTMJAVMc0YevDBYxZYPB8ALd3DkA9o2mPmWriSblYxUc6qAd/uu/6a8QtgW7ecZxdVivMLB18ta5oXrfWKzHZaYNw6T4K/xnBLidUZSVgkSCCpUilKvi6DcQ7Ox0kC47Ejiz27T5UAFxgpzASLYiA0AaudQo30rK/M52Ruu/d+V7mDwdOmTWItsCy7QSwVdlLdYD1dtSZciW6w5mMLES8gGfGuFMUzI3c/3t2LcXufqiW0z6uZMkhAPs7f7ttIG0akiT2vhIIqZAcZTAwEN6xv8ACNJOYwsKJhm5aCQ3vRzxouuVh4m11i3ba3FuNdtLbQq4cBl60vMbCHXb9K0UQQZ52JHSNVX4iyWyw65HyAhlJxGVQrEQoVMrbgRI251oouJbz6qVQFuqrXrmx5j/AGkTyAGiTyAlz4VoA5597LM4rOxVwbQCIgiBB12jUb8tfNzs/PPPhtzu55570D8WYYf9nUApEKIE25JlkEjUZidxvuQdXbOe5557khMi69cs3LLqjHORAXqRo7amcxjIFMtIHakmdyKgse0x57PlSc1wIB8tvfzK2kxGderuw0xmiCAzaK6+DZSvmvgZfDvAlh02KNfDy264/jOGNl2A9CBEid6arTAdZecxpByuWc2KeB2m58z30GgKgpMk2CWlxiROY+9OITlrQEpFMNodh9aaQnJEi6F1OTb736U03RBGfuSMSe1/tX6VRpVaf295SyaZNCC62i+f6UEzRcqC1MjCG43ZPmKCLR1glzRTQvKdRXIkWSXOp865OBYKstAqxTFFTOqQpq0iUpoFIEiao1qJ+1TOieoqTtikSiy6etIfuQm6bbTWkceqEjnWW5wPhz3XRFGrsFE7SfGoVCJWGtUk5Rr8r7RwRHwOECuoLC7lInTtECQakLlaKNR+EwxJF88eK08alrDtcxDMFzJk10GgkR41wutOIbSwz3VyYLgQB2/KxeF4lcfhnR5LIp7XOWDAfKuPYvMwzji8O5lT7mCQd8yrlvo3bULDkFVtxtMpLA+9ESr/APS2CDngwDs4r5n0l4o17EFnOsxpoNNKeI0Xmhz6xNR+pXadFuKLZsvcbXLZswvNmJYKo8SSB61GoYC9f6GzpKzxsgT4lVgwzPdxLMRq10ABldiQqJb3gnRQIDCCKAp5B2nbzyF9VmzG2i9h8QXYux7TRuZyruqLpoqgabzGbtbLB3aqAQFrW3CqDyP05c/CZ5QO4llMLoWF0i43b6u9YVgXNu5IGsdkzm/D+mojnT06d5XB0EJCvN3D6kaXT2d/9Mchtqa9ENmeCxgwsjBh8TbdF3uPA0JgHFLJ0IMCSfShGVjeIXOOaqVQxeMRbj2Qe1bZkIjLsYJCg7Hzk8yBVmtdAJ286/PcovImAq9s9Y6r+Ige8D+n9IgF4gEnnnnaVOJSOMjqsRdtgEBHKgakwNATIBnXuG/iaVhzNBKZ7MphRZHXAlrhBtKWtgczMEMCIZYJ9u41Rr200mTMCCmcOxFsQ3K4DnZ3zPcmTd7IGihpOo3UiTm0epOzZyPFJlkX2r3F75ZCrfHbJBPeBz9dDWoObUZIXn18OQZ3Lnbl5oGp5/WpgBI1glKW408/nTwExa2EAJg6H+zRsnMSEDg5duf6UQiIzJF4w3oKo3RVaOqoLUV0ILjaDzrkzRqoJoowhuHsn0rkWjrIJopoXlOorlxFktjqfOuTjRJWgVQpq1MxKQpi0hiUhThU5CmU9AZqBIyKRIhWbaGoPc211IkJmTT1pMwzdyTNdW8FhizRG5ipvcMoUK1QNbK+r8H4GLNjCXROY3QWnYdrL/SozKwGkAKeJn7nRwANlpf4gcXayLaKRDQ575U6UdBK2/Vqj3OFJptGbvXMdJ+mJxFvqiBo05gd+ztHrRGsBZH16+JY0VYsSfZb3+GTBkv+IT/upFq+lt61UHcPdL/xJxZtlSrEEIuxg6lhVRpCh9TbmxjR/wCA918vvYmW/wDNMGnKmZThq6rhQIt2rckdk4l+ZEk27A7QK5QovvDaarqJkTptDnElfR/TqIo0J2uMq7xbHOrLZJUC0JfIwOe8wHxop0KW8gynbOpHw0XXuO757/Zb2W1ScPjo+pO86gxtrrBOnISDFZst1oBst8vi70FHdLQVMpAQZjEscxBnXx5U9KiCJJ80tWrls0LJxis2a29+4wByuocZTlOqkLvqPlWsU+ZWc1XchOu4BnQHrcg1iMSbJOvMBge/fxrs1MGHRPbCQZ9krCxGCawsKQF5FLk/8lM/OtDQ14tBHcVEvLXXkE8QsHFXmPxO1wDlcYuR4rcPbU+M1Roy/bbs2eHxCDuv93554o+AubuISzMMXQTzhmADac9eXPzmp1LCRp6bx8ItbsKpcRxHWXrryDmdtAAoAGkQNBp3bA+NTpCGAK9US5DZusNVMGDr5jcju5nwAFEgbeefWUgartjD27F17UkyqsGjtuWGVwjQSqMWGgZSQfiGxsamZsxoY12bEAyHapPFeTCRKR3EFDlggkmSpXST61OlUInmx/MqxpNccp2+34Kwbt095962tg3XiupZXFp2Ja3TO596eFxaIQZ9D/fOjCaLoWbT1ojVEC6Uza+gp26KgFl6aZchuHbzoItGqiaK6ELnQ+lcmAuhmiioB1rkYQE6mimQLQKYpi1I6pCmrSbUhThUt6mVZtjWs7j1FF2iu2VrO86WWd5VgWtPWpOd1lLNddZ0G4WLuKtBwcpby2E7+lTJssvVrVW0jtN+C+kYTjOHW4cHcUAIxCsxkfEW1J2owq0sVQbOGrN6rSQD37V8x6ZcQz32AaVVmC6zpJiKaJWXDU5JcNJMcNi5nrtPWqBvW7lvyXXYdDOPPZzqrAZsgIMa77VFzYK8+vUq4frUtousTpBxd7znO0wco8gTFWY1Ww1CACdSshCWYAbkgDzOgp8vVK2tZNl2WAuM2MuBHy20fq4MlBbwyC2dNd+rbUCe140oDW4eXbfde67MKoY3ZHBZ1vEk9pmDFybhOoVy7ZuYkRmA74WplsWGz2WmVYtYjvO2/eIE9ofqNaQssmBQ2L63rhQW1eLdxxmAZWuBggAnR4kz39nSVmq06RDc53x3RM89qV9SHBoN0zhl8jrAdxduj+FyP0qrR1QkrWd4K7hSTdZw/wDpopWJ3a9BMnvOmnKpnbBi+ttw7QgBICx+O3yXNtQc/wBmDc0GVCpLqfDKjsffkDVKUk5ibCd2vFKW/wAY3LGwVw3EUncgT4+Na3kBSi5C2MJgDadr5IV7WH61J07ZvFUMcxoxg1jdVkEDQkLVTpaO7Cue6zMS51znOZO5fUD5iqBuUZd3MrvuMoA5ZgqmNQAdIYnv5QeQ0kbHlVW05En+uf73qL3Ror+N4FfcozXkLKpVtLolfuj/AC9dNPQU1N1NhIGloQcXkdqHBW4sKOaXhoI2u2yBvt8FRxDh0s72+hlVwrSLHf62WTxJMjkDbcd0HuJ3HjzrRQMtWPGU8tY9t1UDa1eFmhDm0NGEYQltPWjF0YugY6+gp26JwLL00y6ELnbzrgiEM0UYUMdDQRGqGaKK9NcuQE0QmQigUSmLUzqkKatIdUhT1qV1Mqza3rO+cii7RaOFWayVSbLJUK1sNh5A86g4mVhqVIK+xcK4Vbw9vDXFAUCHuMTpLJE6+JFASbK9OgykKGJNhq4k7xZfMulfEYxN10IP2jEHlvT5cxhZadIVS47CT5lcpi8WWaTzqzKUBelTpBogKsbunrVRTuq5LokxJBkaGj0VkDTBEIWvzTCmERTV3gtycRZ2/wAxPkwNJVbFJx7Cq0GfuN4retW1Wxec3WDG29whFIJN05gMx0PxSd9q5zwGMaW6kL020yarnA6Sq0aleRmPDfaoA2laY2KcFbOIbJyjK0AtoRpKjcER3BgxhgRWimyBLu7nnzUKj7wO9dcmAw2GyoQrM8Em6ynXIWBdFuSDl0zFATpJNS6cudlGzh/fcqdAAzP8/wBLmsPe7V099+8fe61PTuwcEcT/AJPD0Vm5jItvb6nP1mUMTcgZVLELlKEEdozJMg7UOjJMg7ZSsqtAggrGx2Ie4vV5bdq3qClpYzCQSCdIBgSFAmBO1XDDOZxlIawiGCOe5WeBYqxZfNeBKKJCjmR8IJ3A8YNTrh5bZCllzdbRWv8A1c3Rjbt1lBuW7eQI7KmRWICrB1CiBB+VRfS6NrALyde3hHkVrZVzudaIGnZztC5C1di0sbkRvGvwDXlojR4xWwsmoZ52+6zh0NXScGwaWhna5bDkbC+yZQdSPsxpO5XMyztFM502CkQVo47GlbJCB3Jz9q3buX1Ggibp1U+HL1rKQ81NscQPZaaIZ0ZmJ7yub4ac1tgOd7C6DXc3dIPPzNCvYg9h9FoojTu9VS6QGLvLYc55nc9/lpV8HdnesX1RsVhw9ysvrPL2rbC8/Kg6zy9qMI5VBuacvYUYuiG3SnbX0p26JwLL00y5Q52oDVEBRNFFQTpXbVw1QzRRUTXIoSa5FQK4olMBpCkKYpqZCUhPU1IhSIVq0dazvHVUXCy2OHLJrFWBELz65gLuujHBTfIAWYIPh6nlSFu1eORVq1RTpiSV0XTTpClmwMMrCerCsBqVZSNJ5bUWti5Xo4is6oxmHpxlAAd2EbPlfHsdiiSTNWYy610aUBZz3K0BtlrDUBemDbo5V7PRyhHKoz0YXZVd4Rei/bPcy/WpVmzTcOxUo2qA9q6jENGG+0ViOpZVk3Qk5VgiYSRGgQctSaT+LCBtC326R/es287GQNDBiDEGNNeW9SYACJ0n3VCSQY1hdB0bxlpAEBdXMLKFUVoJgLOuUtnyjmQ5URNVrOzQRpzrfnalpU8uuq1eM449dbVblwlYleutsy//AMzSSrJ2T4ljue+sVP7ySd+/+lseP29PJcPg8V8RPN7h93NegxsNCxVnS8ro7PHXuhx2FWytsCEQEjq8xJPVtJmazgOafviSd2/gnLGuAOXYN/yqnELxhjcFsqqux+IN2CFIUrbAmTz001irNrRF5nh+CpfpwdJHj7khci2IzEx/YIBB9QQa1HelDSEBmCwOUqQ2bXTUKTp4Nr5UtgROicAmw1W3wLhqPcBF622QFiES84HMEgWjCzrBB20qVaqGj0kRzx8U9Kk57o9CF0nF+NW7fWBWvFkzAZmtwSsgEgW5jSslKq9xEgJ6tFo2qhxZzct/Ff0V/wDSIXbmctVIl8wNm1GlULGZQVk9F7GdVWPjvqIgH/KtO57O0dsaVPFujw9bLZhwqvTTTEETMKo+IN92Ykac9hoK0fT/APH3rB9U/wAg4fK56a9BeehmijCgmiNUYS2OvpTt0TDRemmXQoY0EQomiuUE6VyO1RNcivVy5Ca5FQK5cUYNKlhMU0hCUhNVqmWpCFZtXNag9vVUXNstbAYrKZmsVanMLDWpZguy4F03bCKQgBzFZ0k6d3vS5dkLDTpV6LnGkYmPLRczxzirX7j3CD2mLbd5mnawLTh6OUXMnbxWFduVpa1eg1qSWqgCpCiaIC6FE0YRhemjC6E3D3crKe4g+xpHNlpCLbEFdXgrGVifszmDgK0No8iWEECA33vTWs/SDoQAYI9lqFM/qMx0PwqjyJB/3Ed+2lRgbFe4MJly33j4lka76BGB7gRbUHnl0BAJkNPx7+6rsC6BRfvWi924pVBFpLjoS6hMnWC3nC2510y6DvoQxroG3W+if9x7Zi3D8Li8M+nmSfdjW0aLE/7it7AcKV7XXNbVna5lXOXy9WLagsVX97Nqe6sr6z2Oyg792s9q1MoB7cxB2acAqvFOH4a0CXuKCS3YtFW0ZVUi2JJmFI7UAFp1jKWZVqPNhPbzZM6g1okyOP5uVhohdmfKFzGQo2VYhVHkABWouDRCzGCbaK7dwDCySRrdZbVvlMMru3koVZ/OKlnBcOy6rTaYLu7vK6DhaW7SAdkBZIkazB7ZkiGgMSZBEFcyLbcnJWe57p282587LVQYGiNixcViEvM7BmILEkgMB2nA0OTmWX3FWp0nMAkeY+VGo5riYI8/hFxDi9sh01zjMn+ZebtbEaiD71ZrHGDChDWmJ58Fu9DMDrbBWcls3GGTN2r57MrtHVqu+mteTjXkkxtPovXoDK1cj0nxgvYi44OhYxt8I7K7abAbV7GBp5KQC8f6i7NWI3WWPNboWOEE0YRUE1w1RQk0wRC9NFFQxrlwUTRXLxNBFRNciomuXKK5cmLbpSUpcUYtilJS5imC2KUlIXFNW2O6pklIXFORR3VFxKQkqzajuqDpUXSt/gzCRIFYKgIK8vFgxquma1bcbD2owCvGD3tOqysTwlCfhoQRoVup4t4GqqXOCL3U2Z+9XbjXJJ4MvdRzv3qn61yYnAlNHO/ekOPcEu7wICmFR+9O3HEqnc4SByqoquV24sla1jN1fwkxoYMbQPvMFEyIJDEQdDOgZEkL6OjV6Wk2oFSv2oI7QObXaI0ExPjOpiu7ANFYjbvVrEXh1NgaaF1iTqWZmkg+AXl4kjQVITnKrANNVL3DVuXHY3sNqRCm6MwUABcwYSDAn1rXSIDBJjuPws9YOc+GiY7R8qvxDAmw2QlZiYUzA1jy2qgc132mVEhzfuEIOIcLNuGY2zJy9m5bczrp2STyPtQDmnQp4qNFwQFYwXAi1sXc9hFJiXuopBkgSCZEwY74pXVmzlJui2m912tlbnCcNgLBzYnEC4fu2cODcZzyBaIFZnuc77QT5DxP5VhSd/Mgd8nwCHjeKOJui4yKiquSzZUSLScweTO0ifAwfjEIw5RG3afYdg37StAZYDQefE9voOKwOJWLt0KiEQwLHUwVGTLLxHaJWBuQLbGJNaKORpzO55+dySrmIhvPPOqsHHjCW2VCQyKoDiRGcsZnkx7Uc8rx92kcw1nDcT6JqYbSBnnn4VPgGDFwnPoNWuNLA9oEsY2bKoY8tUjWRNsS/K0RzCWg3M4yOSuts3xawty8Qoe7JVM7SgYZba5BpAWDr7V5GTpq4YNnJWypW6Jhfu5C+e3cNJr6emyBC+YdiC5xJS/2KqQh0yE4KjCPTKP2Kugo9Mo/YqMLumXv2KuXdOoOBrkenUfsVcj06g4KuRFZCcHXI9Mo/YzXI9MEP7Ia5HpgpC1KVxKMLQJSEowtLKUlGq0hSkpyrUypkp9sVJwU3FavDzFYqwWKvddNhLulQaV41Vl05jVVMBQfKiil5KaE8p9tKMKTivXLdHKua5VHsimDVcPKFUCMDyOh1gg8mB5efjQcCF7/ANExfWNF22491n4hQDqNdQJBmZJJ3PaOx1bUDMczRTvNhHP9f1YL6FupBVJrOzMrDnDAg8+/1189+SbbKi9+yW3YFxMEajfRv705nTeTTtqObYc887kj6bX6pHFnz4lyZ1VfiImO0NYJHLvp6Ahh4+wQxbgYKs8Ztxh7G+tx9xA/1Nu+hTd1hw+FSqIpu7lHDLPWSpKgAIe0gZWOa6ACT2R6jnUazsr83OgVsMzNTgjmStbC8PFvVUUMdCQgXflE6eQMNOhms7673CCbLS3DsaZASsQk+uh5zqR3bSSNtSSCJJR+aTzzz5jnNHPPPrXuXYZQVLZmCgAFjrmk+QBcmTr29SS5FGNLhbnnm2qG3PPPbpkcQ4m+LuD4upRvs0EsobYGOep1bmT4mttCn0bZOp9FCs/MYGg9VooBbtra53AGaC5AtkhtAx0zsB3dlFP3qx1CXuLlZsMACs8X4gbqqgJyrsNAJjkBEVr+n4PoxnOpXhfVMcHO6JmzXj+FislerC8kOQla5NKHJ40ZRzKDboZkQSoyUcwXSvdXXSF2ZTk8K6V0qCveK6UZQlBTBGSo6rwo2XZl42/CguzIWTwoBEFZ0Dl+tZQTtW9wUqpomEkFOVD3UpIQyncnLaPdSFzd6BpncnW8MTyqbqjQl6FxV6zwxjyrM7EsROFertnAOsdgmfw9o+oWYqDqrHbfb1WOthqmwH1WratOgGZSJ0EjUny3qAczYV5dfDPb9wKui08ZijADclSAPWma9pMArK+g9okg+C9nqwUIXlRjsCfIGjZOGk6BX8JgXfYjymW9VWSPWg6o1qLcM9+nPcLqziOEOsTctid5uBcvmDrXNrNOwqrsA9kSW+Pyqj4HQxdViOS5mnwED61QVL6FDoBBhwPCSqr4QkHMQv5tPlvTyDojSa5pDpghZeJwwuKVMF17QJntqqtAhdTHMeo5yjCaboOh0719hhMU3FUpGo1HOxZz4tg3VPmyA63NCUldJVozbCYI2GugNOKbQ3MFuzEmCrb4cKV7akN8JBidO7cGOQ8hprULkHnnnUqwAmFYPXqpFh2UwdAQonlIPZXwEk99TzGdT4ke6sGiLgd4B9QoxSX+smwJRbbapbVxnzaakEzBo5yGzN52HZzCLmBxgi0bRtVjCYZ85e4RnYAfgJUTC9WwVW3PjWetVL7X8Z/K1UabGCwAHYICuXrYA1A0Ea6QO4htUB/C0qdNRURJvzz5qs7FncTAt2jcNy2uYApmlsw2zZVkxHfvESw0F6V3Bp555ClUMAkLneNcYuYgBUzJYMgKuhuRGYlZlmMCSZ2gbQN+HoCld5l3Ou4LHVrZx1NN/sO1ThcILXbdBAJVE1BYgjsb6qCDmbwiZJys95faeediUNDL871ZsYa5cJdgzFjJIG57h4CqUKQ2ry8djC2zdSn3MERujfKvRFUHQheDlcLkFIawO5vYV2Z3YmGXtQ/sPOH/AIR/WpmtB2K7aQO9JOHX8R/g/wDNd0jtyYUm7/Je/Zl/F/xNL0rtyoKLd6NcKv4h7N/SkNV+weiYUG7/AFUPggTo6gf7v6VwruGo9Exw7TofVMs8EdxmBXJzckhR6kanwE0r8c1ljru2p24JztPwmX+FC2AdddndSFP5V/U0jMWahjyGveqOwoptnXt2IE4fC521UmMxDAT4aVV2JvlFjuUW4eRmOm9JuYOZZSMo3MPA8zlpm4iLHVK6gHfao/YxBIZYHPX5mNKPTu2o/p2nQoWwc/AQe/WmFcj7l36cfxusQE+H9+dJZaSXJiMfD5fpQLQhnd2Jqz3fX+tLDd6BLt3qmAeH9+td3qZO8J9u7AiWA8GqTqQJm3giKsCL+KtWsURs7DyCz771F2HaTJA80OncBZx8lcwuNYGMxYn8SZ/YEmpPwzY0jhZTOIdpM8RPutSxbvE5oC+JtBPmVis5bTFvefdYX06rjmEeEeytkudHvrH/AFMw9ln6UWNYLtb5LFVZUdZzxHH2Cu2ccFUDrV0/BYBPqWyzXdGXGYPj/aDXtY2Mw7mz6wjHFo2a4T3jJb+gP1qgoHcPM/CV2KA0LvIexQftw1IQSdyzOxPnqJqopbz5BZTXEyG+JJ9wiXrW+G3H5bQH/KP1pv2xqfNO0V3Hqt8Gpn/p19viJA8WJ+Qmh0tIaKn6LEu+63f8SlPw+OVxvJAB7yfpTiqDuQ/SlpuHHgOfRKfAyP8ALZI1DnOSpGxEARXOAeIkHwWjDPfh352tI7TJ9IWZj8GHJnRoIEnLauaET/8AG8E+Bk/DuY9alY6b/lfUYbGUcUOqb7tPBY6WL2GuSmcAQWRwMoLmF0ghQIkN5d9UcW1ARod45Gui1M6hBNxuPJ4q3g+OhrkOjQElcoTLJIOYqLZjQ/Fp4jnWWrQc1k6medy2U6rHPgbud8eS0sLxiyxdbjkZY7LAqdZ1nOobbkBE1B1N7QDlN934C0thxIBFudqizx+yyEBizSwCgwIgQCLgcud/h0ouovBHVMd3PonYWT9w54R7rKxPSNzayJaMiVdrioXJO47Xw6HZQNPeqjC/uSXW2JDXbls0k+A57lnWsPcxJV3Z3LZdWUBC0TkULuABEAHSOzqK0vLaR6v5WemXVWQ7TdoDPqr9zhqWoa6Abg16kdnWZBuFTCAdw7R1+Gai2q5xhqNVrKbczjAC1uGdHnvk3r7BB91SrAkDZUVVhE9q206GWJE+HuV83jPqzSDkIG6Z9ACuiwnRUsgYMqg6ASS38KjT1ir1cSymcsLy8PRq1m9IXa958Bp3wrdvoiyNPWgEfiQuPYE1jqY1jmxl8DC308G9jpzeIn3WLxHA3LDalJ12YPHmJIFWphlYWn09kj3uonrRPisa5aeZznXx/Sr9G0CIQFZxMylm2/f8gf0pCwLQ15Q5G8P4F/pSFo5JVQ48wr+F4Zn2VbjDUwAlpP8AqPpPkIHiaxVa+TUwO25PALXTo5tk8NO8q/bwNoMBH7Rc5KBlsp5D7w9h51ldUfEjqt3nUrRkYNbncNErHXeruDMRcYbKCGRD3KMoE+VUo0hUYcsjt2lCq/IRm8Nyq8QskMt29JJ1FtiCY5SoiB61TDlkGnS7yPnekrAvAe/TYPwl3rLYkG4SQid4VUH7qiaLSzDEN1J8ShldXsLAeASL3265FlEQSQqAKPFiX1NUEUXZ33JsL+QskHXHRssNvybolw5u2urtAhE1chB2m72JfXyFI+oylV6SqbnQbvJPSplzCymOJ5KEv1KLbgr94nKZaeZAmKU0xiKhfM7I2BUpn9MIi52riUQ8lJ8YNerbasZnZ6FNFpvAebAfImhZKcyYFHNl9FYn5iPnQjigTwRhlHNj4AKvzk/SgWncPVLI3nusjW8g+5P5nJ/lC0Idv8B8ypks3eJ+ITBiyNlQf7A3zaaUs3k+PxCmX7gOeKdax146B3juUkD2XSpGlTFyB3/lRdUqHQ+H4VqzZc6kHzP9zUzUYLArNUpvNytLD2B95wPQ/rFTNQ7Bz5rMaI2uHPGFrYfB2zE3B5Zj88qn61I137ue+E7cJStLvP4B9VsWOGWo2E8yGVh/CXB+VQOLdNjzxhaRgqQ2e/kSFaSyqbXLY8OrQN9QfnTCoXnQ+J+EOibT0c0dw+UlsQWPZAuH8jE/zGrtYOHf+FPpXOsOt3H5KjK5O9u2e9in8pE0/UGpJ8V2WodzT2x8InWB2rjP4W1EH1BH0rgWzYeJRIc0Q9xP/qP6VfrlXbDsfFyx/ly1USdoWV1djLCme+faFWxPESQVKqoOhAVRI7jpr60YG0rOcfV/gMvC35WNexK24GdSomEuSVE75GHaT0NQexk9Ux6L2MF9briG1mZhvFjz4Kja4jhMzSzoW7yLqTtKiViBsSTSvbVLYI8PyvqsHUpVTnaYnY4R+E9rdl56vFW8pkxc60MCefZRl0/s1PMBrI7l6IY+ZgHvC9aweHthgcTbg5dEa7AhVDdk2wDOXTUR40C/NBMk8O0n3RaxzZAEDiNw7ezcUFi3hQzG2Ll4mBlRAgUKIEOxc+uh8qoOkfYN8VjrYrDYe9Wq0d8nwt6LXw+CxF4kjq8MraFjcLXWHcWBZyPAlRVm4J7vv8l5GI/5JhGCKJDjvNh4C/kFp2uj+GspIL3L0/FlAtjyXefGvQw9HI6zRHbqvlPqX1F2JZJe4umwaOr5gHwWnhbCn47xHiOsP/bV3ug2ZPgsFFmYdeqR/wDXwgxptqOxiLhP5WA9yw+lBoc43pjxHsD6pqjmMHUruJ4H1JHose7jGH+o3uT9aqaTNymzE1v9iq/7Q76TP+xT9RSOYxok27ytbKtV5gXPAfCFsSifFlc/hCrl9WA18h71Bwc77ZHaZ9PnwW+jUay7yCdwA8z8eKoIr3WyoCSfuqJ//B50j4Y2XGBvW6k/O7K0SdwVnqrVn/NbrH/9tGhAf37g3PgvvWMvq1f8Qgf7H2HuV6LW0qX+U3/1HuVP7Zcv9kQqjkOzbX/z86Q0adHrOMnebkqgrvq9VggdmiJrvVqQLrBT8UaZjGw7/epgdK4SwE7Pkqx/bbOeN9vRZdrGlGzIYPIkKT8xW19APblf5SsYrgOlvmrYwjXBnuOQW1iMzEd+4ishrspft022HcAtYpvqdd518UHEcQ4VbTMsL9xRAXuzHma7DMYXGoAeJ9karnMbknuHugweHuOhAIVJkknKpbzjU1Sq+mxwJElJSD3Ahuis3MQ1u0q5UCg6QTLnmTrP0rJ0TKtUuzGeGi1h7qTIgRx1WfluX2ZoE7ntBR4ATWpuSi0NlSOes4mFx+XaT5TI+tekCNnPgsTg7bz4qQp7h6EGjmbvSZXbkQnmCB5GhI2IZTtBHcvSPxe4P6TQvuSEA6OHn+U7Kv4vp+sUmY7ufNF1JsWPp+ES4gDYj+GD7rSFhm/r8pJbFo8D7J6Ys959Gb9SamaQ3eQUnVNl/Eqwl4GND7j+lJlI5/KyPI5/pa2ENwD4YH4mJUR5kgVF7WHU+n9pAagFh3mf6V9D+K4vkozH3GnzoAbgs7z/ALOHr6fKfbv2hyZvMhR7a/UU8OUSac6E+A+fZXLGJJ0t219FznT800h7SqMd/wBtg8J9ZU4i/eI7WeO4hoH6VzWt2JnvrH7p8/6VM3aJC5oGiauDuMMwR2B2IUnbyqZfC2MwecSQYUjBzC5XRtO05IQemSfmai+s4C48lrZ9IpO0cQeIV48D2yYgMefaKr6EtJ/hrIcUdvovQp/SKQ3nv/Ksjo7ZVZuMbjz8CmFA7y7KQfakdi3A9X4XoUsHTaftAR2+gNpxncWkBEgFbbGPRR9KqMc8C9QDvv4XK0Do22a2VR4j0IwpgWkzNOpyZF9IYE+1Bv1SpMAk8QBz5KoaNXCO9Ztz/DidrHsbv/2rS36jW3eSm5lA6lU+K/4fthVVw5Ut91LhDKYntKyzTt+phzsrmglZH/T6FeQB5BULRv2tC7MP3iD88tXZiG/xMea8jEf8bY77bd35V21j2P3gPU1tp1p/kvCxH0StR/jI7Fbt9Y2zj3rWxrzoQvKextM9ZpCelm7zePWqilU2pRUp7D6o7i5dS7N4Ake5O3saJpu2COez8KrKjdXOnsE+pHsVTv3Xfs/8VG55Tzb1mubSAudefBWNYuECw3Dbx2nvRnh62tcQxB3FpIN0/m5Wx56+FZ3YjMctIZjv2DifYXW+ngxTaKmIOUbB/I8B7lV8XxFmU27S9WnNEmWHe7/E/rA8KQYVoOeqcx7dBwCq7GvPUoNyt7PuPE/HmqNqxG6sxPwiMoHiWPLy966q8/xiNv8ASphmj+QJJ0A9ZVfF3FXRZn7x5T3Ac/OuosqOEv02b1as6m0wyZ23twQ2LLXIJ0WYzEyPbcnwpnuayw13LmNfU4b1afB5Azdb2V+E5D2vHX4fnUP1EkNLbnt5lahhTBcDYdh5Hmqy8Scn4yTMgwCZ8D31R2FpREJGYmrMkptzDOCBoWiWGsrOwadM3hNZxWZsFhYdvBasjzc6m/PFPxVy7ZRZdI1Crpm31MR85rOzoq9QgNPHZ6+y1kVKLJJCrW7ty+YEHKJ1IVQBz7hV3NZRGY7fFSDn1SGgT7KzguIvbSAqQST2ozHzGb9KhVosqOuTz3K9GtUpNgNHPeubu2gVDGSY3JJ+tV6VzXlrbDgFR9Jr2BzrniUzhllWW4WVSVQkdkaGKGIrPaWAHUhSwtCm9zsw0BWOjEc69IgHVec0kCxRm634j6kmlyNGxEvcRBK9NFRAUqaUpXLoOCYK26ksskeJ/Q15+Jqua4AFNRY185kn9scEgELr9xVQ+6gGnDAQCVmrOLXENsmo5JkmT3nWhACwvMm6u22rlmIXY9EeGWrqM9xMxExJMaeEwa8/FVnsnKV6n07C0qt3ifFGvELikopUL+EW0A9gKn0bXNzOue0lP076bzTZAHYAPZX+N4lrFiy9o5GfOGKgAkAactPSlo0mVKpa4WCvjK76GHY+mYJJk23FV+jPDrV23cd0zMNiSfpMVXF1XMaMpUfpmHp1XHOJ8U9OH2yQMg38RXjVMZW3+Q+F9HTwlJt2jzPysq7iHt3mRHdVB0Adh+tbKZLqQcdVqH3QtLCY+5zcnb4u19ai+o9uhPiVdtJh1AW1gLxbcL/Ag+grP+oeXQY8B8IPpNAt6lbdvBIVkr8yPoa9CjSY/Ue3osbqjgdVWu4ZVOg+Zo1MPTGgTMqOOqS91tdT71heACrgBZWMQGZFKLaKrSud4neYKUDMEMyoYhTO+m1aKTjmiVSAbrkcSIOlevT0WWsBCixcOmtbKTiDZfNfUKLDNlqYa80b/wBxXrU3FfI1WNk2VgOTzq4JUcoWhjWNjCJdtdl3cKzj4spmQCfh8xFeZiCX4htJx6p1C9/AsazCvrtHWGh1i/bZZqKBadwBmDJBIDfEe0ddye/etbwGubTbYbhZZaLi9r6rruG039VmOddNPLT6VVzQbFSY4i4ScRebLEmCT493P1NI2iwOmLrY2vULIJsqCauo5EgHyJpnmASqUwDAK6W8oVggACrIUAbf1PjXkM6zS46leuTlcGt0CxuL3WMKSYGscp7/ABrVgGNOZxF5hTx7iAxoNolL4J/mqeYBI8wNDXfUHEUHEKeBaHV2g6Kw7k5dTrqdTqTqTWCAMwA0XqAkkE7VS40ftmHIEAQI0gd2/nV8A0dA 
# Techonologies used:

 1. Machine Learning
 2. Random forest algorithm
