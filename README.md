# 📜 About me

```elixir
defmodule User do
  def create_user do
    %{
      name: "Shantanu Chaubey",
      role: "Full Stack Developer",
      languages: ["Hindi", "English"],
      education: "BSc @ REVA University"
    }
    |> (fn user ->
          """
          Name: #{user.name}
          Role: #{user.role}
          Spoken Languages: #{Enum.join(user.languages, ", ")}
          Education: #{user.education}
          """
        end).()
    |> IO.puts()
  end
end

User.create_user()

```

## 🛠️ Skills

<details open>
  <summary><b>📌 Programming languages</b></summary>
  <br>

[![Programming Languages](https://skillicons.dev/icons?i=python,js,typescript,go)](https://skillicons.dev)
</details>

<details open>
  <summary><b>📚 Libraries and Frameworks</b></summary>
  <br>

[![Libraries and Frameworks](https://skillicons.dev/icons?i=react,nextjs,express,tailwind,django)](https://skillicons.dev)
</details>

<details open>
  <summary><b>🎨 Markup and Style Languages</b></summary>
  <br>

[![Markup and Style Languages](https://skillicons.dev/icons?i=html,css,markdown)](https://skillicons.dev)
</details>

<details open>
  <summary><b>🧠 DevOps</b></summary>
  <br>

[![DevOps Tools](https://skillicons.dev/icons?i=docker,aws,vercel)](https://skillicons.dev)
</details>

<details open>
  <summary><b>🗄️ Databases</b></summary>
  <br>

[![Databases](https://skillicons.dev/icons?i=mysql,postgres,mongo)](https://skillicons.dev)
</details>

<details open>
  <summary><b>🔧 Software and Tools</b></summary>
  <br>

[![Software and Tools](https://skillicons.dev/icons?i=git,github,vscode,linux,postman,obsidian,figma)](https://skillicons.dev)
</details>

<details open>
  <summary><b>🔧 CRM & Web Builders</b></summary>
  <br>

[![CRM & Web Builders](https://skillicons.dev/icons?i=wordpress)](https://skillicons.dev)
</details>

## 📊 Github stats and extras

[![visitcount](https://visitcount.itsvg.in/api?id=4joejoe&label=Profile%20Views&color=11&icon=6&pretty=true)](https://visitcount.itsvg.in)
